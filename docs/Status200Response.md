# Status200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**version** | **str** | The current version of the Flow AI Server. | [optional] 

## Example

```python
from flow.models.status200_response import Status200Response

# TODO update the JSON string below
json = "{}"
# create an instance of Status200Response from a JSON string
status200_response_instance = Status200Response.from_json(json)
# print the JSON string representation of the object
print(Status200Response.to_json())

# convert the object into a dict
status200_response_dict = status200_response_instance.to_dict()
# create an instance of Status200Response from a dict
status200_response_from_dict = Status200Response.from_dict(status200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


