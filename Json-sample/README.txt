Json namespace provides functionality for serializing to and deserializing from
JavaScript Object Notation (JSON).
Serialization is the process of converting the state of an object, that is, the values of its
properties, into a form that can be stored or transmitted.

-JSON objects are easy to read and write;

-A tree structure JSON data:
    *Navigated;
    *Analyzed;
    *Or modified;

-Provides immutable object models for JSON object and array structures;

-Uses builder patterns to create these object models from scratch:
    -JsonObjectBuilder to create models of JSON objects;
    -JsonArrayBuilder to create models of JSON arrays;
    -Or from an input source (such as InputStream or Reader) using the interface JsonReader.

