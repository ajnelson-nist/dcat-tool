# dcat-tool

[DCAT](https://www.w3.org/TR/vocab-dcat-3/) is the Data Catalog Vocabulary, a product of the World Wide Web
Consortium (WC3)'s Dataset Exchange Working Group.

This repo contains a tool that is intended to have the following
functionality:

1. Given an RDF schema, generate an Excel spreadsheet that can be used
  as a collection instrument for that schema.  (It's envisioned that
  the RDF Schema will be a subset of DCAT, because we don't want to
  collect with every attribute in the schema.)

  The excel spreadsheet should contain minimal validation.

2. Given a spreadsheet that's been filled out, parse the supplied data
in the spreadsheet into its RDF representation.

3. Given an RDF representation of data elements, validate them, and
   create sensible error messages if validation fails. (We will use
   this to create web-forms that allow people to upload either RDF
   data or spreadsheets.)



# For additional Reference

These sites may be useful:

* [rdflib documentation](https://rdflib.readthedocs.io/en/stable/)
* [SHACL: Shapes Constraint Language, a W3C Recommendation](https://www.w3.org/TR/shacl/)
* [OWL 2 Web Ontology Language Overview](https://www.w3.org/TR/owl2-overview/)
* [W3C RDF 1.1 Primer](https://www.w3.org/TR/rdf11-primer/)

## Related Concepts


Turtle
: An easy-to-author format for rendering RDF as text.

RDF/XML
: A rendering of RDF data into XML.

JSON-LD
: The JavaScript Object Notation Linked Data format, a specification
: based on JSON.
