# PROJECT ORACLE R1 — Public Anchor

**Publication date:** 2026-09-30
**Target event:** Austrian Lotto 6 aus 45 draw on 2026-09-30

## Primary marker
`ORACLE-R1-6cdcc0c7496c80de29aa4bb165a69124`

## Secondary authentication token
`6b3c5cacc02ae4fd502cba27da089373`

## Purpose
This file is a public, timestamped preregistration anchor for a speculative information-causality experiment.

At the time of this commit, the official Austrian Lotto 6 aus 45 draw for 2026-09-30 has not yet taken place.

The experiment asks whether any future public source can later be found that contains this exact marker together with the official six main numbers for the target draw, and whether any independently verifiable timestamp or indexing evidence shows that such a payload was publicly accessible before the draw.

## Future payload format
A future public record associated with this experiment should use the following exact structure:

```
ORACLE-R1-6cdcc0c7496c80de29aa4bb165a69124
AUTH-6b3c5cacc02ae4fd502cba27da089373
DRAW-2026-09-30
NUMBERS-AA-BB-CC-DD-EE-FF
```

where `AA-BB-CC-DD-EE-FF` are the six official Austrian Lotto 6 aus 45 main numbers for the draw on 2026-09-30, written in ascending order with two digits each.

## Integrity rule
This anchor file must not be edited after its initial publication. Any later observations or results must be added in separate files or later commits so the original state remains preserved in Git history.

## Prior local protocol hash
SHA-256:
`5f8dacc47dcc75a95e59a300bf98d898c4abf355aa53cdfae2fa69eb85e25a8b`

## Interpretation
A later appearance of the marker together with the correct numbers would not by itself prove retrocausality. Strong evidence would require independently verifiable timestamps showing pre-draw availability and successful replication under a preregistered protocol.
