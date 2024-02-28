# BackupItem

## Properties

|Name | Type | Description | Notes|
|------------ | ------------- | ------------- | -------------|
|**Created** | Pointer to [**time.Time**](time.Time.md) | The ISO 8601 creation timestamp. | [optional] |
|**Size** | Pointer to **int32** | The size of the backup in Mebibytes (MiB). This is the size of the binary backup file that was stored.  | [optional] |

## Methods

### NewBackupItem

`func NewBackupItem() *BackupItem`

NewBackupItem instantiates a new BackupItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBackupItemWithDefaults

`func NewBackupItemWithDefaults() *BackupItem`

NewBackupItemWithDefaults instantiates a new BackupItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *BackupItem) GetCreated() time.Time`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *BackupItem) GetCreatedOk() (*time.Time, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *BackupItem) SetCreated(v time.Time)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *BackupItem) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetSize

`func (o *BackupItem) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *BackupItem) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *BackupItem) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *BackupItem) HasSize() bool`

HasSize returns a boolean if a field has been set.


