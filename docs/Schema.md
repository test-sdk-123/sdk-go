# Schema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StringProperty** | Pointer to **string** | Property name&#39;s description (type is string) | [optional] 
**ReadOnlyStringProperty** | Pointer to **string** | Notice this only appears in the response. | [optional] [readonly] 
**WriteOnlyStringProperty** | Pointer to **string** | Notice this only appears in the request. | [optional] 
**MinLengthString** | Pointer to **string** | Property name&#39;s description (type is string) | [optional] 
**MaxLengthString** | Pointer to **string** | Property name&#39;s description (type is string) | [optional] 
**MinAndMaxLengthString** | Pointer to **string** | Property name&#39;s description (type is string) | [optional] 
**NullableOrStringProperty** | Pointer to **NullableString** | Property name&#39;s description (type is string or null) | [optional] 
**StringEnumValues** | Pointer to **string** | Property name&#39;s description (type is string) | [optional] 
**StringDateTime** | Pointer to **time.Time** | Property name&#39;s description (type is string, format is date-time) | [optional] 
**StringDate** | Pointer to **string** | Property name&#39;s description (type is string, format is date-time) | [optional] 
**StringEmail** | Pointer to **string** | Property name&#39;s description (type is string, format is email) | [optional] 
**StringIpAddressV4** | Pointer to **string** | Property name&#39;s description (type is string, format is ipv4 address) | [optional] 
**StringIpAddressV6** | Pointer to **string** | Property name&#39;s description (type is string, format is ipv6 address) | [optional] 
**StringPassword** | Pointer to **string** | Property name&#39;s description (type is string, format is password) | [optional] 
**StringHostname** | Pointer to **string** | Property name&#39;s description (type is string, format is hostname) | [optional] 
**StringUri** | Pointer to **string** | Property name&#39;s description (type is string, format is uri) | [optional] 
**StringUuid** | Pointer to **string** | Property name&#39;s description (type is string, format is uuid) | [optional] 
**NumberProperty** | Pointer to **float32** | Property name&#39;s description (type is number) | [optional] 
**NumberFloat** | Pointer to **float32** | Property name&#39;s description (type is number, format is float) | [optional] 
**NumberDouble** | Pointer to **float64** | Property name&#39;s description (type is number, format is double) | [optional] 
**NumberGreaterThanOrEquals** | Pointer to **float32** | Property name&#39;s description (type is number) | [optional] 
**NumberGreaterThan** | Pointer to **float32** | Property name&#39;s description (type is number) | [optional] 
**NumberLessThan** | Pointer to **float32** | Property name&#39;s description (type is number) | [optional] 
**NumberLessThanOrEquals** | Pointer to **float32** | Property name&#39;s description (type is number) | [optional] 
**NumberRange** | Pointer to **float32** | Property name&#39;s description (type is number) | [optional] 
**NumberRangeExclusiveMaximum** | Pointer to **float32** | Property name&#39;s description (type is number) | [optional] 
**NumberRangeExclusiveMinimumAndMaximum** | Pointer to **float32** | Property name&#39;s description (type is number) | [optional] 
**NumberMultipleOf** | Pointer to **float32** | Property name&#39;s description (type is number) | [optional] 
**IntegerType** | Pointer to **int32** | Property name&#39;s description (type is integer) | [optional] 
**Integer32bit** | Pointer to **int32** | Property name&#39;s description (type is integer, format is int32) | [optional] 
**Integer64bit** | Pointer to **int64** | Property name&#39;s description (type is integer, format is int64) | [optional] 
**BooleanProperty** | Pointer to **bool** | Property name&#39;s description (type is boolean) | [optional] 

## Methods

### NewSchema

`func NewSchema() *Schema`

NewSchema instantiates a new Schema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSchemaWithDefaults

`func NewSchemaWithDefaults() *Schema`

NewSchemaWithDefaults instantiates a new Schema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStringProperty

`func (o *Schema) GetStringProperty() string`

GetStringProperty returns the StringProperty field if non-nil, zero value otherwise.

### GetStringPropertyOk

`func (o *Schema) GetStringPropertyOk() (*string, bool)`

GetStringPropertyOk returns a tuple with the StringProperty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringProperty

`func (o *Schema) SetStringProperty(v string)`

SetStringProperty sets StringProperty field to given value.

### HasStringProperty

`func (o *Schema) HasStringProperty() bool`

HasStringProperty returns a boolean if a field has been set.

### GetReadOnlyStringProperty

`func (o *Schema) GetReadOnlyStringProperty() string`

GetReadOnlyStringProperty returns the ReadOnlyStringProperty field if non-nil, zero value otherwise.

### GetReadOnlyStringPropertyOk

`func (o *Schema) GetReadOnlyStringPropertyOk() (*string, bool)`

GetReadOnlyStringPropertyOk returns a tuple with the ReadOnlyStringProperty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadOnlyStringProperty

`func (o *Schema) SetReadOnlyStringProperty(v string)`

SetReadOnlyStringProperty sets ReadOnlyStringProperty field to given value.

### HasReadOnlyStringProperty

`func (o *Schema) HasReadOnlyStringProperty() bool`

HasReadOnlyStringProperty returns a boolean if a field has been set.

### GetWriteOnlyStringProperty

`func (o *Schema) GetWriteOnlyStringProperty() string`

GetWriteOnlyStringProperty returns the WriteOnlyStringProperty field if non-nil, zero value otherwise.

### GetWriteOnlyStringPropertyOk

`func (o *Schema) GetWriteOnlyStringPropertyOk() (*string, bool)`

GetWriteOnlyStringPropertyOk returns a tuple with the WriteOnlyStringProperty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWriteOnlyStringProperty

`func (o *Schema) SetWriteOnlyStringProperty(v string)`

SetWriteOnlyStringProperty sets WriteOnlyStringProperty field to given value.

### HasWriteOnlyStringProperty

`func (o *Schema) HasWriteOnlyStringProperty() bool`

HasWriteOnlyStringProperty returns a boolean if a field has been set.

### GetMinLengthString

`func (o *Schema) GetMinLengthString() string`

GetMinLengthString returns the MinLengthString field if non-nil, zero value otherwise.

### GetMinLengthStringOk

`func (o *Schema) GetMinLengthStringOk() (*string, bool)`

GetMinLengthStringOk returns a tuple with the MinLengthString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinLengthString

`func (o *Schema) SetMinLengthString(v string)`

SetMinLengthString sets MinLengthString field to given value.

### HasMinLengthString

`func (o *Schema) HasMinLengthString() bool`

HasMinLengthString returns a boolean if a field has been set.

### GetMaxLengthString

`func (o *Schema) GetMaxLengthString() string`

GetMaxLengthString returns the MaxLengthString field if non-nil, zero value otherwise.

### GetMaxLengthStringOk

`func (o *Schema) GetMaxLengthStringOk() (*string, bool)`

GetMaxLengthStringOk returns a tuple with the MaxLengthString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLengthString

`func (o *Schema) SetMaxLengthString(v string)`

SetMaxLengthString sets MaxLengthString field to given value.

### HasMaxLengthString

`func (o *Schema) HasMaxLengthString() bool`

HasMaxLengthString returns a boolean if a field has been set.

### GetMinAndMaxLengthString

`func (o *Schema) GetMinAndMaxLengthString() string`

GetMinAndMaxLengthString returns the MinAndMaxLengthString field if non-nil, zero value otherwise.

### GetMinAndMaxLengthStringOk

`func (o *Schema) GetMinAndMaxLengthStringOk() (*string, bool)`

GetMinAndMaxLengthStringOk returns a tuple with the MinAndMaxLengthString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinAndMaxLengthString

`func (o *Schema) SetMinAndMaxLengthString(v string)`

SetMinAndMaxLengthString sets MinAndMaxLengthString field to given value.

### HasMinAndMaxLengthString

`func (o *Schema) HasMinAndMaxLengthString() bool`

HasMinAndMaxLengthString returns a boolean if a field has been set.

### GetNullableOrStringProperty

`func (o *Schema) GetNullableOrStringProperty() string`

GetNullableOrStringProperty returns the NullableOrStringProperty field if non-nil, zero value otherwise.

### GetNullableOrStringPropertyOk

`func (o *Schema) GetNullableOrStringPropertyOk() (*string, bool)`

GetNullableOrStringPropertyOk returns a tuple with the NullableOrStringProperty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNullableOrStringProperty

`func (o *Schema) SetNullableOrStringProperty(v string)`

SetNullableOrStringProperty sets NullableOrStringProperty field to given value.

### HasNullableOrStringProperty

`func (o *Schema) HasNullableOrStringProperty() bool`

HasNullableOrStringProperty returns a boolean if a field has been set.

### SetNullableOrStringPropertyNil

`func (o *Schema) SetNullableOrStringPropertyNil(b bool)`

 SetNullableOrStringPropertyNil sets the value for NullableOrStringProperty to be an explicit nil

### UnsetNullableOrStringProperty
`func (o *Schema) UnsetNullableOrStringProperty()`

UnsetNullableOrStringProperty ensures that no value is present for NullableOrStringProperty, not even an explicit nil
### GetStringEnumValues

`func (o *Schema) GetStringEnumValues() string`

GetStringEnumValues returns the StringEnumValues field if non-nil, zero value otherwise.

### GetStringEnumValuesOk

`func (o *Schema) GetStringEnumValuesOk() (*string, bool)`

GetStringEnumValuesOk returns a tuple with the StringEnumValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringEnumValues

`func (o *Schema) SetStringEnumValues(v string)`

SetStringEnumValues sets StringEnumValues field to given value.

### HasStringEnumValues

`func (o *Schema) HasStringEnumValues() bool`

HasStringEnumValues returns a boolean if a field has been set.

### GetStringDateTime

`func (o *Schema) GetStringDateTime() time.Time`

GetStringDateTime returns the StringDateTime field if non-nil, zero value otherwise.

### GetStringDateTimeOk

`func (o *Schema) GetStringDateTimeOk() (*time.Time, bool)`

GetStringDateTimeOk returns a tuple with the StringDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringDateTime

`func (o *Schema) SetStringDateTime(v time.Time)`

SetStringDateTime sets StringDateTime field to given value.

### HasStringDateTime

`func (o *Schema) HasStringDateTime() bool`

HasStringDateTime returns a boolean if a field has been set.

### GetStringDate

`func (o *Schema) GetStringDate() string`

GetStringDate returns the StringDate field if non-nil, zero value otherwise.

### GetStringDateOk

`func (o *Schema) GetStringDateOk() (*string, bool)`

GetStringDateOk returns a tuple with the StringDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringDate

`func (o *Schema) SetStringDate(v string)`

SetStringDate sets StringDate field to given value.

### HasStringDate

`func (o *Schema) HasStringDate() bool`

HasStringDate returns a boolean if a field has been set.

### GetStringEmail

`func (o *Schema) GetStringEmail() string`

GetStringEmail returns the StringEmail field if non-nil, zero value otherwise.

### GetStringEmailOk

`func (o *Schema) GetStringEmailOk() (*string, bool)`

GetStringEmailOk returns a tuple with the StringEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringEmail

`func (o *Schema) SetStringEmail(v string)`

SetStringEmail sets StringEmail field to given value.

### HasStringEmail

`func (o *Schema) HasStringEmail() bool`

HasStringEmail returns a boolean if a field has been set.

### GetStringIpAddressV4

`func (o *Schema) GetStringIpAddressV4() string`

GetStringIpAddressV4 returns the StringIpAddressV4 field if non-nil, zero value otherwise.

### GetStringIpAddressV4Ok

`func (o *Schema) GetStringIpAddressV4Ok() (*string, bool)`

GetStringIpAddressV4Ok returns a tuple with the StringIpAddressV4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringIpAddressV4

`func (o *Schema) SetStringIpAddressV4(v string)`

SetStringIpAddressV4 sets StringIpAddressV4 field to given value.

### HasStringIpAddressV4

`func (o *Schema) HasStringIpAddressV4() bool`

HasStringIpAddressV4 returns a boolean if a field has been set.

### GetStringIpAddressV6

`func (o *Schema) GetStringIpAddressV6() string`

GetStringIpAddressV6 returns the StringIpAddressV6 field if non-nil, zero value otherwise.

### GetStringIpAddressV6Ok

`func (o *Schema) GetStringIpAddressV6Ok() (*string, bool)`

GetStringIpAddressV6Ok returns a tuple with the StringIpAddressV6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringIpAddressV6

`func (o *Schema) SetStringIpAddressV6(v string)`

SetStringIpAddressV6 sets StringIpAddressV6 field to given value.

### HasStringIpAddressV6

`func (o *Schema) HasStringIpAddressV6() bool`

HasStringIpAddressV6 returns a boolean if a field has been set.

### GetStringPassword

`func (o *Schema) GetStringPassword() string`

GetStringPassword returns the StringPassword field if non-nil, zero value otherwise.

### GetStringPasswordOk

`func (o *Schema) GetStringPasswordOk() (*string, bool)`

GetStringPasswordOk returns a tuple with the StringPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringPassword

`func (o *Schema) SetStringPassword(v string)`

SetStringPassword sets StringPassword field to given value.

### HasStringPassword

`func (o *Schema) HasStringPassword() bool`

HasStringPassword returns a boolean if a field has been set.

### GetStringHostname

`func (o *Schema) GetStringHostname() string`

GetStringHostname returns the StringHostname field if non-nil, zero value otherwise.

### GetStringHostnameOk

`func (o *Schema) GetStringHostnameOk() (*string, bool)`

GetStringHostnameOk returns a tuple with the StringHostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringHostname

`func (o *Schema) SetStringHostname(v string)`

SetStringHostname sets StringHostname field to given value.

### HasStringHostname

`func (o *Schema) HasStringHostname() bool`

HasStringHostname returns a boolean if a field has been set.

### GetStringUri

`func (o *Schema) GetStringUri() string`

GetStringUri returns the StringUri field if non-nil, zero value otherwise.

### GetStringUriOk

`func (o *Schema) GetStringUriOk() (*string, bool)`

GetStringUriOk returns a tuple with the StringUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringUri

`func (o *Schema) SetStringUri(v string)`

SetStringUri sets StringUri field to given value.

### HasStringUri

`func (o *Schema) HasStringUri() bool`

HasStringUri returns a boolean if a field has been set.

### GetStringUuid

`func (o *Schema) GetStringUuid() string`

GetStringUuid returns the StringUuid field if non-nil, zero value otherwise.

### GetStringUuidOk

`func (o *Schema) GetStringUuidOk() (*string, bool)`

GetStringUuidOk returns a tuple with the StringUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringUuid

`func (o *Schema) SetStringUuid(v string)`

SetStringUuid sets StringUuid field to given value.

### HasStringUuid

`func (o *Schema) HasStringUuid() bool`

HasStringUuid returns a boolean if a field has been set.

### GetNumberProperty

`func (o *Schema) GetNumberProperty() float32`

GetNumberProperty returns the NumberProperty field if non-nil, zero value otherwise.

### GetNumberPropertyOk

`func (o *Schema) GetNumberPropertyOk() (*float32, bool)`

GetNumberPropertyOk returns a tuple with the NumberProperty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberProperty

`func (o *Schema) SetNumberProperty(v float32)`

SetNumberProperty sets NumberProperty field to given value.

### HasNumberProperty

`func (o *Schema) HasNumberProperty() bool`

HasNumberProperty returns a boolean if a field has been set.

### GetNumberFloat

`func (o *Schema) GetNumberFloat() float32`

GetNumberFloat returns the NumberFloat field if non-nil, zero value otherwise.

### GetNumberFloatOk

`func (o *Schema) GetNumberFloatOk() (*float32, bool)`

GetNumberFloatOk returns a tuple with the NumberFloat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberFloat

`func (o *Schema) SetNumberFloat(v float32)`

SetNumberFloat sets NumberFloat field to given value.

### HasNumberFloat

`func (o *Schema) HasNumberFloat() bool`

HasNumberFloat returns a boolean if a field has been set.

### GetNumberDouble

`func (o *Schema) GetNumberDouble() float64`

GetNumberDouble returns the NumberDouble field if non-nil, zero value otherwise.

### GetNumberDoubleOk

`func (o *Schema) GetNumberDoubleOk() (*float64, bool)`

GetNumberDoubleOk returns a tuple with the NumberDouble field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberDouble

`func (o *Schema) SetNumberDouble(v float64)`

SetNumberDouble sets NumberDouble field to given value.

### HasNumberDouble

`func (o *Schema) HasNumberDouble() bool`

HasNumberDouble returns a boolean if a field has been set.

### GetNumberGreaterThanOrEquals

`func (o *Schema) GetNumberGreaterThanOrEquals() float32`

GetNumberGreaterThanOrEquals returns the NumberGreaterThanOrEquals field if non-nil, zero value otherwise.

### GetNumberGreaterThanOrEqualsOk

`func (o *Schema) GetNumberGreaterThanOrEqualsOk() (*float32, bool)`

GetNumberGreaterThanOrEqualsOk returns a tuple with the NumberGreaterThanOrEquals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberGreaterThanOrEquals

`func (o *Schema) SetNumberGreaterThanOrEquals(v float32)`

SetNumberGreaterThanOrEquals sets NumberGreaterThanOrEquals field to given value.

### HasNumberGreaterThanOrEquals

`func (o *Schema) HasNumberGreaterThanOrEquals() bool`

HasNumberGreaterThanOrEquals returns a boolean if a field has been set.

### GetNumberGreaterThan

`func (o *Schema) GetNumberGreaterThan() float32`

GetNumberGreaterThan returns the NumberGreaterThan field if non-nil, zero value otherwise.

### GetNumberGreaterThanOk

`func (o *Schema) GetNumberGreaterThanOk() (*float32, bool)`

GetNumberGreaterThanOk returns a tuple with the NumberGreaterThan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberGreaterThan

`func (o *Schema) SetNumberGreaterThan(v float32)`

SetNumberGreaterThan sets NumberGreaterThan field to given value.

### HasNumberGreaterThan

`func (o *Schema) HasNumberGreaterThan() bool`

HasNumberGreaterThan returns a boolean if a field has been set.

### GetNumberLessThan

`func (o *Schema) GetNumberLessThan() float32`

GetNumberLessThan returns the NumberLessThan field if non-nil, zero value otherwise.

### GetNumberLessThanOk

`func (o *Schema) GetNumberLessThanOk() (*float32, bool)`

GetNumberLessThanOk returns a tuple with the NumberLessThan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberLessThan

`func (o *Schema) SetNumberLessThan(v float32)`

SetNumberLessThan sets NumberLessThan field to given value.

### HasNumberLessThan

`func (o *Schema) HasNumberLessThan() bool`

HasNumberLessThan returns a boolean if a field has been set.

### GetNumberLessThanOrEquals

`func (o *Schema) GetNumberLessThanOrEquals() float32`

GetNumberLessThanOrEquals returns the NumberLessThanOrEquals field if non-nil, zero value otherwise.

### GetNumberLessThanOrEqualsOk

`func (o *Schema) GetNumberLessThanOrEqualsOk() (*float32, bool)`

GetNumberLessThanOrEqualsOk returns a tuple with the NumberLessThanOrEquals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberLessThanOrEquals

`func (o *Schema) SetNumberLessThanOrEquals(v float32)`

SetNumberLessThanOrEquals sets NumberLessThanOrEquals field to given value.

### HasNumberLessThanOrEquals

`func (o *Schema) HasNumberLessThanOrEquals() bool`

HasNumberLessThanOrEquals returns a boolean if a field has been set.

### GetNumberRange

`func (o *Schema) GetNumberRange() float32`

GetNumberRange returns the NumberRange field if non-nil, zero value otherwise.

### GetNumberRangeOk

`func (o *Schema) GetNumberRangeOk() (*float32, bool)`

GetNumberRangeOk returns a tuple with the NumberRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberRange

`func (o *Schema) SetNumberRange(v float32)`

SetNumberRange sets NumberRange field to given value.

### HasNumberRange

`func (o *Schema) HasNumberRange() bool`

HasNumberRange returns a boolean if a field has been set.

### GetNumberRangeExclusiveMaximum

`func (o *Schema) GetNumberRangeExclusiveMaximum() float32`

GetNumberRangeExclusiveMaximum returns the NumberRangeExclusiveMaximum field if non-nil, zero value otherwise.

### GetNumberRangeExclusiveMaximumOk

`func (o *Schema) GetNumberRangeExclusiveMaximumOk() (*float32, bool)`

GetNumberRangeExclusiveMaximumOk returns a tuple with the NumberRangeExclusiveMaximum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberRangeExclusiveMaximum

`func (o *Schema) SetNumberRangeExclusiveMaximum(v float32)`

SetNumberRangeExclusiveMaximum sets NumberRangeExclusiveMaximum field to given value.

### HasNumberRangeExclusiveMaximum

`func (o *Schema) HasNumberRangeExclusiveMaximum() bool`

HasNumberRangeExclusiveMaximum returns a boolean if a field has been set.

### GetNumberRangeExclusiveMinimumAndMaximum

`func (o *Schema) GetNumberRangeExclusiveMinimumAndMaximum() float32`

GetNumberRangeExclusiveMinimumAndMaximum returns the NumberRangeExclusiveMinimumAndMaximum field if non-nil, zero value otherwise.

### GetNumberRangeExclusiveMinimumAndMaximumOk

`func (o *Schema) GetNumberRangeExclusiveMinimumAndMaximumOk() (*float32, bool)`

GetNumberRangeExclusiveMinimumAndMaximumOk returns a tuple with the NumberRangeExclusiveMinimumAndMaximum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberRangeExclusiveMinimumAndMaximum

`func (o *Schema) SetNumberRangeExclusiveMinimumAndMaximum(v float32)`

SetNumberRangeExclusiveMinimumAndMaximum sets NumberRangeExclusiveMinimumAndMaximum field to given value.

### HasNumberRangeExclusiveMinimumAndMaximum

`func (o *Schema) HasNumberRangeExclusiveMinimumAndMaximum() bool`

HasNumberRangeExclusiveMinimumAndMaximum returns a boolean if a field has been set.

### GetNumberMultipleOf

`func (o *Schema) GetNumberMultipleOf() float32`

GetNumberMultipleOf returns the NumberMultipleOf field if non-nil, zero value otherwise.

### GetNumberMultipleOfOk

`func (o *Schema) GetNumberMultipleOfOk() (*float32, bool)`

GetNumberMultipleOfOk returns a tuple with the NumberMultipleOf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberMultipleOf

`func (o *Schema) SetNumberMultipleOf(v float32)`

SetNumberMultipleOf sets NumberMultipleOf field to given value.

### HasNumberMultipleOf

`func (o *Schema) HasNumberMultipleOf() bool`

HasNumberMultipleOf returns a boolean if a field has been set.

### GetIntegerType

`func (o *Schema) GetIntegerType() int32`

GetIntegerType returns the IntegerType field if non-nil, zero value otherwise.

### GetIntegerTypeOk

`func (o *Schema) GetIntegerTypeOk() (*int32, bool)`

GetIntegerTypeOk returns a tuple with the IntegerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntegerType

`func (o *Schema) SetIntegerType(v int32)`

SetIntegerType sets IntegerType field to given value.

### HasIntegerType

`func (o *Schema) HasIntegerType() bool`

HasIntegerType returns a boolean if a field has been set.

### GetInteger32bit

`func (o *Schema) GetInteger32bit() int32`

GetInteger32bit returns the Integer32bit field if non-nil, zero value otherwise.

### GetInteger32bitOk

`func (o *Schema) GetInteger32bitOk() (*int32, bool)`

GetInteger32bitOk returns a tuple with the Integer32bit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInteger32bit

`func (o *Schema) SetInteger32bit(v int32)`

SetInteger32bit sets Integer32bit field to given value.

### HasInteger32bit

`func (o *Schema) HasInteger32bit() bool`

HasInteger32bit returns a boolean if a field has been set.

### GetInteger64bit

`func (o *Schema) GetInteger64bit() int64`

GetInteger64bit returns the Integer64bit field if non-nil, zero value otherwise.

### GetInteger64bitOk

`func (o *Schema) GetInteger64bitOk() (*int64, bool)`

GetInteger64bitOk returns a tuple with the Integer64bit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInteger64bit

`func (o *Schema) SetInteger64bit(v int64)`

SetInteger64bit sets Integer64bit field to given value.

### HasInteger64bit

`func (o *Schema) HasInteger64bit() bool`

HasInteger64bit returns a boolean if a field has been set.

### GetBooleanProperty

`func (o *Schema) GetBooleanProperty() bool`

GetBooleanProperty returns the BooleanProperty field if non-nil, zero value otherwise.

### GetBooleanPropertyOk

`func (o *Schema) GetBooleanPropertyOk() (*bool, bool)`

GetBooleanPropertyOk returns a tuple with the BooleanProperty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBooleanProperty

`func (o *Schema) SetBooleanProperty(v bool)`

SetBooleanProperty sets BooleanProperty field to given value.

### HasBooleanProperty

`func (o *Schema) HasBooleanProperty() bool`

HasBooleanProperty returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


