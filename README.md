# swift-formatter-pair

Pair integration for the Formatter domain.

A `Pair` whose elements conform to `Formatter.Protocol` becomes a formatter
for paired inputs. Each formatter receives its corresponding input, the output
is a `Pair` of both results, and failures retain their origin as the left or
right case of `Either`.
