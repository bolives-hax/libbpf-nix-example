# WIP!! 

should build a rust program using libbpf, its quite simple and crude but
gets you a foot in the door. 

```sh
nix build "github:bolives-hax/libbpf-nix-example"
```
or
```sh
git clone https://github.com/bolives-hax/libbpf-nix-example
cd libbpf-nix-example
nix build .#
./result/bin/netfilter_blocklist
```

`nix run` can be used instead of nix build. Though ebpf stuff usually reqiures root 
