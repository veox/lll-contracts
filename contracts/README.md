# contracts

* `collapser`: self-destructs to itself on any invocation.
* `greeter`: returns 42; allows changing the value.
* `graffiti`: push data into ERC20 contracts' allowance fields


## Notes

The `factory` contract has been moved to the [`lll-creation-patterns`][lcp]
repo and renamed to `stamping-press`.

Same goes for `cloning-vat` - it hasn't been renamed.

Sorry for the broken links! The last commit here to have them is `6d7ea234`:
on [gitlab][factory-commit] or [github][factory-backup] (backup).

[lcp]: https://gitlab.com/veox/lll-creation-patterns
[factory-commit]: https://gitlab.com/veox/lll-contracts/tree/6d7ea2345b21044f8b4393c25b32f2d7dfb67ec7/contracts
[factory-backup]: https://github.com/veox/lll-contracts/tree/6d7ea2345b21044f8b4393c25b32f2d7dfb67ec7/contracts

The `multisend` contract has been moved to the [`lll-multisend`][lms] repo.
The last commit in this repo to have it is `c572ee6f`: view on
[gitlab][multisend-commit] or [github][multisend-backup] (backup).

[lms]: https://gitlab.com/veox/lll-multisend
[multisend-commit]: https://gitlab.com/veox/lll-contracts/tree/c572ee6f6bcc66f61060a41cdc704caaa2b85e11/contracts
[multisend-backup]: https://github.com/veox/lll-contracts/tree/c572ee6f6bcc66f61060a41cdc704caaa2b85e11/contracts
