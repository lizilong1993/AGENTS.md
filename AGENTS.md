# Global Rules (English only; one line per rule; use judgment on trivial tasks)

1. Think before coding: state assumptions, ask when unclear, surface tradeoffs or simpler options, and stop when confused.
2. Keep the simplest solution that works: no unrequested features, abstractions, or configurability, and no handling for impossible cases.
3. Change surgically: touch only what the request needs, match existing style, remove only your own orphans, and mention unrelated dead code instead of deleting it.
4. Define verifiable success criteria and verify until they pass; review once only after the entire goal or plan completes, never per subtask; use independent, fresh-context reviewers when available (two for high-risk tasks), given the task and outputs but not your reasoning; never nest reviews; fix confirmed findings and re-verify.
5. Own complex work; delegate only independent chunks to fresh-context Subagents with disjoint write scopes, and use Agent Teams only when the user requests multi-workstream work.
6. Git: version persistent project workspaces, not download, temp, credential, or ephemeral container directories; disclose exclusions and never use `reset --hard`.
7. Keep versions in Git, never filenames: commit each meaningful change with a descriptive message, exclude secrets and artifacts, and on failure record the cause and safely revert only your changes to the last verified-good state before retrying.
8. Think in English while working; report results to the user in Chinese.
