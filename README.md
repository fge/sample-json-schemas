<h1>What this repository is</h1>

<p>This repository contains sample JSON Schemas for various JSON-based formats found around the
web.</p>

<p>There are many such formats, and this repository contains schemas for whatever formats I happened
to stumble upon.</p>

<h1>Existing schemas in this repository</h1>

<p>This repository contains schemas for the following:</p>

<ul>
    <li>JSON-RPC 2.0 (<a href="http://www.jsonrpc.org/specification">link to
    specification</a>);</li>
    <li>GeoJSON (<a href="http://www.geojson.org/geojson-link to specification.html">spec</a>);</li>
    <li>SMD (<a href="http://livedocs.dojotoolkit.org/dojox/rpc/smd">link to
    specification</a>);</li>
    <li>JSON Patch (<a href="http://tools.ietf.org/html/draft-ietf-appsawg-json-patch-10">link to
    specification</a>);</li>
    <li>Avro Schema 1.7.3 (<a href="http://avro.apache.org/docs/current/link to
    specification.html">link to specification</a>).</li>
</ul>

<p>Note: these schemas may not be perfect. I have used <a
href="https://github.com/fge/json-schema-validator">my library</a> to test these schemas with
various data samples, and while I am fully confident about the library itself, I am not that
confident about the schemas themselves: I <i>have</i> read the relevant specifications, but some
obscure points may have escaped me. Not to mention that some constraints expressed by said
specifications are not enforceable by JSON Schema proper.</p>

<h1>Requests and contributions</h1>

<p>Both are welcomed:</p>

<ul>
    <li>if you stumble upon a JSON data format which you would like a JSON Schema for, feel free to
    open a feature request so that a schema be written for that format;</li>
    <li>if, on the other hand, you have written a schema for an existing format, and wish to add it
    to this repository, you are welcome to open a pull request so that this schema be included in
    the examples. Provided that you are ready to comply to the...</li>
</ul>

<h1>Licensing conditions</h1>

<p>The licensing conditions are the same as they are for JSON Schema itself: content in this
repository may be licensed under either of the AFL or BSD license.</p>

