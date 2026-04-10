# heartbeat

This folder contains a hearbeat application.

## Using the component

Define the heartbeat dependency in the manifest idf_component.yml.

## Example

To run the provided example, create it as follows:

```bash
idf.py create-project-from-example "peterhouwen/esp-idf_components/components/hearbeat:heartbeat-example"
```

Then build as usual:
```bash
cd heartbeat-example
idf.py build
```

And flash it to the board:
```bash
idf.py -p PORT flash monitor
```

## License

This component is provided under Apache 2.0 license, see [LICENSE](LICENSE.md) file for details.