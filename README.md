# projects

A monorepo of standalone projects, each included as a Git submodule.

## Projects

- **[drum-machine](./drum-machine)** — NEON PADS, a client-side drum machine
  built with Next.js, Tailwind CSS, and the Web Audio API.
  Repo: https://github.com/Aanya63/neon-drum-machine

## Working with submodules

Clone this repo with its submodules:

```bash
git clone --recurse-submodules https://github.com/Aanya63/projects.git
```

If you already cloned it without `--recurse-submodules`:

```bash
git submodule update --init --recursive
```

Pull the latest commits for every submodule:

```bash
git submodule update --remote --merge
```
