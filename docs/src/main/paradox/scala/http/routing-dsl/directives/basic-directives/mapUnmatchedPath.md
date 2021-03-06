<a id="mapunmatchedpath"></a>
# mapUnmatchedPath

## Signature

FIXME@@snip [BasicDirectives.scala](../../../../../../../../../akka-http/src/main/scala/akka/http/scaladsl/server/directives/BasicDirectives.scala) { #mapUnmatchedPath }

## Description

Transforms the unmatchedPath field of the request context for inner routes.

The `mapUnmatchedPath` directive is used as a building block for writing @ref[Custom Directives](../custom-directives.md#custom-directives). You can use it
for implementing custom path matching directives.

Use `extractUnmatchedPath` for extracting the current value of the unmatched path.

## Example

@@snip [BasicDirectivesExamplesSpec.scala](../../../../../../../test/scala/docs/http/scaladsl/server/directives/BasicDirectivesExamplesSpec.scala) { #mapUnmatchedPath-example }