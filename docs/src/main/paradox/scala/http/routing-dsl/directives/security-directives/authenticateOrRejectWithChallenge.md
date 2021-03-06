<a id="authenticateorrejectwithchallenge"></a>
# authenticateOrRejectWithChallenge

## Signature

FIXME@@snip [SecurityDirectives.scala](../../../../../../../../../akka-http/src/main/scala/akka/http/scaladsl/server/directives/SecurityDirectives.scala) { #authentication-result }

FIXME@@snip [SecurityDirectives.scala](../../../../../../../../../akka-http/src/main/scala/akka/http/scaladsl/server/directives/SecurityDirectives.scala) { #authenticateOrRejectWithChallenge }

## Description

Lifts an authenticator function into a directive.

This directive allows implementing the low level challange-response type of authentication that some services may require.

More details about challenge-response authentication are available in the [RFC 2617](http://tools.ietf.org/html/rfc2617), [RFC 7616](http://tools.ietf.org/html/rfc7616) and [RFC 7617](http://tools.ietf.org/html/rfc7617).

## Example

@@snip [SecurityDirectivesExamplesSpec.scala](../../../../../../../test/scala/docs/http/scaladsl/server/directives/SecurityDirectivesExamplesSpec.scala) { #authenticateOrRejectWithChallenge-0 }