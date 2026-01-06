## Files

### [my_schema.json](/my_schema.json)

This is a schema file that describe how a json should be structured.

E.g. It describe what are the object keys, and which ones are compulsory.

### [my_usage.json](../my_usage.json) and [my_usage.yaml](../my_usage.yaml)

These are example usage of the json schema defined in `my_schema.json`.

Since json and yaml are interchangeable in most cases, the data of the two files are exactly the same.

`$schema` is the specialy key that declares which schema the file is following.
It is optional, but once defined, most code editors (with or without plugins) honors it.

## Example reallife usage

Using IntelliJ IDEA as an example,

When all required fields are provided, no error is shown:

![img.png](/docs/img.png)

If I missed an compulsory field, an error is shown:

![img_1.png](/docs/img_1.png)

It also autocompletes as I type:

![img_2.png](/docs/img_2.png)
