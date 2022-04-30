# Rosetta 蛋白相互作用

1.蛋白结构的RELAX

```ROSSETA
flag_relax 文件

-nstruct 20
-relax:default_repeats 5

$resetta3/relax.default.linuxclangrelease -s complex.pdb @flag_relax
```