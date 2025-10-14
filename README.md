# Example.com Go SDK

## Overview

This is an **example** API to demonstrate features of the OpenAPI specification. # Introduction This API definition is intended to to be a good starting point for describing your API in [OpenAPI/Swagger format](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.2.md). It also demonstrates features of the [create-openapi-repo](https://github.com/Redocly/create-openapi-repo) tool and the [Redoc](https://github.com/Redocly/Redoc) documentation engine. Beyond the standard OpenAPI syntax, we use a few  [vendor extensions](https://github.com/Redocly/Redoc/blob/master/docs/redoc-vendor-extensions.md). # OpenAPI Specification The goal of The OpenAPI Specification is to define a standard, language-agnostic interface to REST APIs which allows both humans and computers to discover and understand the capabilities of the service without access to source code, documentation, or through network traffic inspection. When properly defined via OpenAPI, a consumer can  understand and interact with the remote service with a minimal amount of implementation logic. Similar to what interfaces have done for lower-level programming, OpenAPI removes the guesswork in calling the service. 

## Installation

```bash
go get github.com/GIT_USER_ID/GIT_REPO_ID
```

## Configuration

```go
import (
    "context"
    openapi "github.com/GIT_USER_ID/GIT_REPO_ID"
)

// Create configuration with API key
cfg := openapi.NewConfiguration()
cfg.AddDefaultHeader("api-key", "your_api_key_here")

// Create API client
client := openapi.NewAPIClient(cfg)
```

## Example Request

```go
// Get brand data by domain
ctx := context.Background()
request := openapi.DomainRequest{
    Domain: "example.com",
}

response, _, err := client.BrandsAPI.ByDomain(ctx).
    DomainRequest(request).
    Execute()

if err != nil {
    log.Fatal(err)
}

// Access brand data
fmt.Printf("Brand: %s\n", response.Brand.Name)
fmt.Printf("Logo: %s\n", response.Images.Logos[0].Url)
fmt.Printf("Primary Color: %s\n", response.Colors.Primary[0].Hex)
```

## API Endpoints

Class | Method | Description
------------ | ------------- | -------------
*EchoAPI* | **Echo** | Echo test


## Models

List of available API Models

[Example.com Models](http://localhost:4321/docs/api-docs/models)

## Authentication

Authentication schemes defined for the API:

[Example.com Authentication Documentation](http://localhost:4321/docs/authentication)


### api_key

- **Type**: API key
- **API key parameter name**: api_key
- **Location**: HTTP header

