# ErrResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**err** | **str** |  | [optional] 
**msg** | **str** |  | [optional] 
**fields** | **Dict[str, str]** |  | [optional] 

## Example

```python
from flow.models.err_response import ErrResponse

# TODO update the JSON string below
json = "{}"
# create an instance of ErrResponse from a JSON string
err_response_instance = ErrResponse.from_json(json)
# print the JSON string representation of the object
print(ErrResponse.to_json())

# convert the object into a dict
err_response_dict = err_response_instance.to_dict()
# create an instance of ErrResponse from a dict
err_response_from_dict = ErrResponse.from_dict(err_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


