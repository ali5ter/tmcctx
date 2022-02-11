# tmctx + tmcmc + tmcp: Tools for VMware Tanzu Mission Control CLI

Inspired by [kubectx](https://github.com/ahmetb/kubectx), this repository provides [tmctx](tmcctx), [tmcmc](tmcmc) and [tmcp](tmcp) utilities.

[tmctx](tmcctx) helps you switch between VMware Tanzu Mission Control (TMC) CLI contexts.

[tmcmc](tmcmc) helps you switch between VMware Tanzu Mission Control (TMC) CLI management clusters.

[tmcp](tmcp) helps you switch between VMware Tanzu Mission Control (TMC) CLI provisioners.

Note: If you have [fzf](https://github.com/junegunn/fzf) installed, selection of context, management cluster and provisioners is made much easier!

## Installing
1. Make sure you have the `tmc` CLI installed.
2. Clone this repository
3. Put [tmctx](tmcctx), [tmcmc](tmcmc) and [tmcmp](tmcmp) into your `$PATH` or move them, e.g.
```shell
ln -sf $PWD/tmctx /usr/local/bin/tmctx
ln -sf $PWD/tmcmc /usr/local/bin/tmcmc
ln -sf $PWD/tmcp /usr/local/bin/tmcp
```

## Other Tanzu Mission Control CLI stuff
If you're using TMC CLI and want to be reminded of your context, management cluster and provisioner, take a look at my [tmc-prompt](https://github.com/ali5ter/tmc-prompt).

If you're curious about the TMC CLI and looking for examples, take a look at [my scripts I use to understand the usability and functionality of the TMC CLI](https://github.com/ali5ter/vmware_scripts/tree/master/tmc).

Also, if you're at all interested in CLI taxonomy, check out [cli_taxo](https://github.com/ali5ter/cli_taxo).
