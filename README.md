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
    <li>GeoJSON (<a href="http://www.geojson.org/geojson-spec.html">link to specification</a>);</li>
    <li>SMD (<a href="http://livedocs.dojotoolkit.org/dojox/rpc/smd">link to
    specification</a>);</li>
    <li>JSON Patch (<a href="http://tools.ietf.org/html/draft-ietf-appsawg-json-patch-10">link to
    specification</a>);</li>
    <li>Avro Schema 1.7.4 (<a href="http://avro.apache.org/docs/current/spec.html">link to
    specification</a>);</li>
    <li>JSON Home (<a href="http://tools.ietf.org/html/draft-nottingham-json-home-02">link to
    specification</a>);</li>
    <li>JSON Stat (<a href="http://json-stat.org/format/">link to
    specification</a>).</li>
    <li>Swagger 1.2 (<a href="https://github.com/wordnik/swagger-spec/blob/master/versions/1.2.md">link
    to specification</a>).</li>
</ul>

<p>Note: these schemas are probably not perfect. See below.</p>

<h1>How these schemas are written and tested</h1>

<p>I use <a href="http://json-schema-validator.herokuapp.com">my toy site</a> to check both the
validity of the schema syntax, and the validation of data against these schemas.</p>

<p>This site uses <a href="https://github.com/fge/json-schema-validator">my library</a>, which I am
fully confident about. But I am not that confident about the schemas themselves.</p>

<p>I <i>have</i> read the relevant specifications, but I certainly have missed some points in them,
and as a result these schemas may not be accurate. Not to mention that some constraints expressed
by these specifications are not enforceable by JSON Schema.</p>

<h1>Requests and contributions</h1>

<p>Both are welcome:</p>

<ul>
    <li>if you stumble upon a JSON data format which you would like a JSON Schema for, feel free to
    open a feature request so that a schema be written for that format;</li>
    <li>if you spot an error on a schema (data which should validate but does not, or the opposite),
    you can provide sample data and the expected and actual results, using the site above; or you
    can submit a pull request to improve the schema itself;
    <li>if, on the other hand, you have written a schema for an existing format, and wish to add it
    to this repository, you are welcome to open a pull request so that this schema be included in
    the examples. Provided that you are ready to comply to the...</li>
</ul>

<h1>Licensing conditions</h1>

<p>The licensing conditions are the same as they are for JSON Schema itself: content in this
repository may be licensed under either of the AFL or BSD license.</p>

