# hh.ht
A full scripting language + GC + FFI + 38-page docs in a single 190632-byte binary

- Reference-counting GC  
- Full C FFI (loadlib + dynamic .so)  
- Ordered LJSON objects with directional traversal (=> =< =+ =-)  
- Bytecode save/load (savebc/loadbc)  
- Depends only on libc · Runs on any Linux since glibc 2.34

File size: **190632 bytes** (exactly, -O2, x86_64 Linux)

```bash
$ chmod +x hh
$ ./hh -h           # 交互式帮助，38 个主题
$ ./hh -h 1         # 查看“关于 hh.ht”
$ ./hh -h 32        # 查看“hello world”
