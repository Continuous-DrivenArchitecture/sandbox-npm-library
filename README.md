# sandbox-npm-library

**Sandbox repository.** Created from
[`template-npm-library`](https://github.com/Continuous-DrivenArchitecture/template-npm-library)
to validate the CDA repository factory (template generation +
`repository-provisioner`) end to end — repository creation, Bootstrap,
initialization PR, `ci-required` execution, and Finalize. Not intended for
real-world use, and not published to npm while it remains `private: true`.

It implements **CDA npm Library Profile v1** (which extends **CDA
Repository Standard v1**) exactly as the template does, and carries no
domain logic of its own — `src/index.ts` exports a single placeholder
function whose only job is to prove the source → build → package →
consumption chain works.

See `COMPLIANCE.md` for the requirement-by-requirement mapping this
repository inherited from the template, and `CONTRIBUTING.md` for the
branching/PR/release model in effect here.
