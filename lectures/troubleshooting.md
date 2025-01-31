---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Julia
  language: julia
  name: julia-1.6
---

(troubleshooting)=
```{raw} html
<div id="qe-notebook-header" style="text-align:right;">
        <a href="https://quantecon.org/" title="quantecon.org">
                <img style="width:250px;display:inline;" src="https://assets.quantecon.org/img/qe-menubar-logo.svg" alt="QuantEcon">
        </a>
</div>
```

# Troubleshooting

```{contents} Contents
:depth: 2
```

This troubleshooting page is to help ensure you software environment is setup correctly
to run this lecture set locally on your machine.

## Fixing Your Local Environment

To set up a standard desktop environment, you can run the instructions in our [local setup lecture](https://julia.quantecon.org/getting_started_julia/getting_started.html#Desktop-Installation-of-Julia-and-Jupyter).

If you already have, make sure to try deleting your `.julia` directory (the "user depot," where packages are stored) and re-running the lectures.

You can find this directory by running `DEPOT_PATH[1]` in a Julia REPL.

## Upgrading Julia

See the {ref}`lecture section <upgrading_julia>` on getting vscode and Jupyter working with a new version.

## Resetting a JupyterHub Lecture Set

The lectures are delivered to JupyterHubs using `nbgitpuller`.

To reset a single notebook, simply delete it and click the relevant link again.

To reset your whole lecture set, run `rm -rf lecture-julia.notebooks` in the Terminal (after `cd`-ing to where they're downloaded, which is usually the root) and click any lecture's link again.

## Reporting an Issue

One way to give feedback is to raise an issue through our [issue tracker](https://github.com/QuantEcon/lecture-source-py/issues).

Please be as specific as possible.  Tell us where the problem is and as much
detail about your local set up as you can provide.

Another feedback option is to use our [discourse forum](https://discourse.quantecon.org/).

Finally, you can provide direct feedback to [contact@quantecon.org](mailto:contact@quantecon.org)

