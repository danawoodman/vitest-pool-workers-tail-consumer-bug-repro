# Tail Consumer Bug

Reproduction for https://github.com/cloudflare/workers-sdk/issues/9343

```bash
bun install
bun run test
```

Comment out `tail_consumers` in `wrangler.jsonc` to see the test pass.
