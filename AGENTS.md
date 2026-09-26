# Unexplained phenomena site guide

This is a static HTML/CSS research site. `index.html` links the topic pages and asteroid simulators; the individual HTML files carry their own browser scripts. There is no package manifest, CI, dependency install, or declared test/lint/typecheck/build command.

For content changes, preserve citations and distinguish observation, hypothesis, and speculation; historical scores or claims in the README are not independently verified research. Check local links, anchors, and changed scientific assertions against their sources. For an optional local preview, a standard static server such as `python3 -m http.server 8000 --bind 127.0.0.1` can serve the repository; this is a suggested preview command, not a project build system.

For simulator/layout changes, inspect the actual page, console, controls, and representative output in a browser. Check external script availability separately from local source correctness. A screenshot of one frame does not validate an animation or scientific model. Publishing and changes to external hosting are separate from local preview.

## Completing work

Carry the authorized change through the relevant checks and repair failures it causes. Make routine, reversible implementation choices using existing patterns; ask only when missing information, a material product decision, or an authorization boundary prevents the next step. Existing authorization remains valid within its scope. If blocked, name the exact action and missing prerequisite, retain concise evidence, and continue independent work.

Choose verification proportional to the change. For instructions or prose, inspect changed paths, links, and local instruction precedence and run `git diff --check -- <changed-paths>`; don't install dependencies or run the application solely for a prose edit. For behavior changes, exercise the affected behavior and applicable checks below, then broaden only for failures or unresolved risk. Report files changed, checks actually run and their results, commands only inspected, and remaining limitations. A build or source inspection alone does not prove runtime behavior. Continue through already-authorized follow-through; stop at explicit review checkpoints or boundaries requiring new authorization.
