# Random notes

## Proof techniques

- Use `split` to proof about functions with `if` to obtain the cases
- `simpa using` to get a easy corollary


## Advanced stuff

- Don't rewrite `⊢ Decidable _` as `rw/simp` will introduce a `Eq.rec` term that can't be reduced by the kernel.
