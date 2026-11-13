# Signing and Evidence Guide

## 1. Before signing

- Identify the actual rights holder for every contribution.
- Check employment, contractor, client, university, funding, and assignment agreements.
- Separate original project material from third-party dependencies and copied snippets.
- Define the scope by paths and immutable commit or archive hashes.
- Obtain company or co-owner authorization where needed.

## 2. Signatures

Use a signature method that is legally recognized for the relevant parties and jurisdictions. A typed name, Git commit, pull-request comment, or checkbox may or may not qualify as an enforceable electronic signature.

Keep:

- the signed original (PDF or e-signature provider export);
- date/time and signature audit trail;
- signer's identity and capacity;
- evidence of corporate authority, if applicable;
- covered commit SHA, tag, archive hash, and file list;
- any exclusions and separate third-party permissions.

Do not commit sensitive identity documents, home addresses, or private contact details to a public repository.

## 3. Public register

Update `AUTHORS.md` only after the release has been received and checked. A public register can use a contributor's chosen public name and a non-sensitive record identifier. Store the signed original securely elsewhere unless the signer expressly agrees to public disclosure.

## 4. Pull-request workflow

A practical workflow is:

1. Contributor submits the change and identifies its source.
2. Maintainer checks whether the contribution contains third-party material.
3. Contributor signs `CONTRIBUTOR-RELEASE.md` for the precise contribution scope.
4. If the contribution was created for an employer or client, obtain that rights holder's authorization or signature.
5. Maintainer records the release and covered commit in `AUTHORS.md`.
6. Only then include the contribution in the project's CC0-dedicated body.

If a release is missing or disputed, keep the contribution excluded until resolved.

## 5. Repository integrity

- Preserve signed records and their hashes.
- Do not rewrite or backdate timestamps.
- Use immutable tags or archive hashes to identify covered snapshots.
- Keep a change log when the scope of a release is expanded.
- Re-audit third-party notices when dependencies or generated files change.
