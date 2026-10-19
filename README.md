# Engineering Tools

Browser-based calculators by Peter Janus. Each tool is a single self-contained HTML page with no install or server needed.

## Tools

| Tool | Folder | Description |
|---|---|---|
| Bus Bar Sizing & Estimating Tool | [`busbar/`](busbar/) | Sizes copper/aluminum bus bar from load (amps, kW or kVA), accounts for mounting holes, lists passing stock alternatives, and estimates weight and material cost. |

## Using a tool

- **Online:** with GitHub Pages enabled, each tool is at `https://pjinfo73git.github.io/calcs/<folder>/`.
- **Offline:** download the folder's `index.html` and open it in any browser.

## Changing defaults

Each page has an `EDITABLE CONFIG BLOCK` near the top of its `index.html` (current densities, safety factor, stock sizes, voltages, default values). Edit and commit; "Reset to Defaults" in the tool returns to these values.
