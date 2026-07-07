# Cathedral SN39 signed weight feed

Public static mirror for the signed Cathedral validator weight vector.

Primary object:

```text
/v1/validator/weights/next
```

The payload is signed by the Cathedral weight-policy Ed25519 key. Validators must verify signature, network, netuid, expiry, and monotonic policy version before applying.
