# Backup

## Properties

|Name | Type | Description | Notes|
|------------ | ------------- | ------------- | -------------|
|**ClusterId** | Pointer to **string** | The unique ID of the cluster that was backed up. | [optional] |
|**Items** | Pointer to [**[]BackupItem**](BackupItem.md) |  | [optional] |

## Methods

### NewBackup

`func NewBackup() *Backup`

NewBackup instantiates a new Backup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBackupWithDefaults

`func NewBackupWithDefaults() *Backup`

NewBackupWithDefaults instantiates a new Backup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClusterId

`func (o *Backup) GetClusterId() string`

GetClusterId returns the ClusterId field if non-nil, zero value otherwise.

### GetClusterIdOk

`func (o *Backup) GetClusterIdOk() (*string, bool)`

GetClusterIdOk returns a tuple with the ClusterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterId

`func (o *Backup) SetClusterId(v string)`

SetClusterId sets ClusterId field to given value.

### HasClusterId

`func (o *Backup) HasClusterId() bool`

HasClusterId returns a boolean if a field has been set.

### GetItems

`func (o *Backup) GetItems() []BackupItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *Backup) GetItemsOk() (*[]BackupItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *Backup) SetItems(v []BackupItem)`

SetItems sets Items field to given value.

### HasItems

`func (o *Backup) HasItems() bool`

HasItems returns a boolean if a field has been set.


