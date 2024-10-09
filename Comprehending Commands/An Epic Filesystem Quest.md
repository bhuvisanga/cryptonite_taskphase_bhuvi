In this challenge we use `cd`, `ls` and `cat` to find the flag.
```
Connected!
hacker@commands~an-epic-filesystem-quest:~$ cat  /opt/linux/linux-5.4/arch/powerpc/include/asm/GIST-TRAPPED
Yahaha, you found me!
The next clue is in: /usr/lib/ruby/2.7.0/bundler/templates/newgem/test

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:~$ cd /usr/lib/ruby/2.7.0/bundler/templates/newgem/test
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/bundler/templates/newgem/test$ ls
LEAD  newgem_test.rb.tt  test_helper.rb.tt
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/bundler/templates/newgem/test$ cat LEAD
Great sleuthing!
The next clue is in: /usr/local/lib/python3.8/dist-packages/angr/procedures/java_jni

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/bundler/templates/newgem/test$  /usr/local/lib/python3.8/dist-packages/angr/procedures/java_jni ls
ssh-entrypoint: /usr/local/lib/python3.8/dist-packages/angr/procedures/java_jni: Is a directory
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/bundler/templates/newgem/test$ ls
LEAD  newgem_test.rb.tt  test_helper.rb.tt
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/bundler/templates/newgem/test$ ls  /usr/local/lib/python3.8/dist-packages/angr/procedures/java_jni
BLUEPRINT-TRAPPED  array_operations.py                global_and_local_refs.py  object_operations.py
__init__.py        class_and_interface_operations.py  method_calls.py           string_operations.py
__pycache__        field_access.py                    not_implemented.py        version_information.py
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/bundler/templates/newgem/test$ cat BLUEPRINT-TRAPPED
cat: BLUEPRINT-TRAPPED: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/bundler/templates/newgem/test$ cat /usr/local/lib/python3.8/dist-packages/angr/procedures/java_jni/BLUEPRINT-TRAPPED
Yahaha, you found me!
The next clue is in: /usr/local/lib/python3.8/dist-packages/cle/backends/pe
hacker@commands~an-epic-filesystem-quest:/usr/lib/ruby/2.7.0/bundler/templates/newgem/test$ cd  /usr/local/lib/python3.8/dist-packages/cle/backends/pe
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/cle/backends/pe$ ls
POINTER  __init__.py  __pycache__  pe.py  regions.py  relocation  symbol.py
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/cle/backends/pe$  /usr/local/lib/python3.8/dist-packages/cle/backends/pe/POINTER
ssh-entrypoint: /usr/local/lib/python3.8/dist-packages/cle/backends/pe/POINTER: Permission denied
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/cle/backends/pe$ cat POINTER
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/arch/arm64/boot/dts/xilinx

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/cle/backends/pe$ cd /opt/linux/linux-5.4/arch/arm64/boot/dts/xilinx
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/arch/arm64/boot/dts/xilinx$ ls
CLUE                    zynqmp-zc1254-revA.dts       zynqmp-zc1751-xm018-dc4.dts  zynqmp-zcu102-revB.dts
Makefile                zynqmp-zc1275-revA.dts       zynqmp-zc1751-xm019-dc5.dts  zynqmp-zcu104-revA.dts
avnet-ultra96-rev1.dts  zynqmp-zc1751-xm015-dc1.dts  zynqmp-zcu100-revC.dts       zynqmp-zcu106-revA.dts
zynqmp-clk.dtsi         zynqmp-zc1751-xm016-dc2.dts  zynqmp-zcu102-rev1.0.dts     zynqmp-zcu111-revA.dts
zynqmp-zc1232-revA.dts  zynqmp-zc1751-xm017-dc3.dts  zynqmp-zcu102-revA.dts       zynqmp.dtsi
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/arch/arm64/boot/dts/xilinx$ cat CLUE
Congratulations, you found the clue!
The next clue is in: /opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_internal/metadata/importlib/__pycache__

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/arch/arm64/boot/dts/xilinx$ ls /opt/pwndbg/.venv/lib/python3.8/site-packages/pip/_internal/metadata/importlib/__pycache__
README-TRAPPED  __init__.cpython-38.pyc  _compat.cpython-38.pyc  _dists.cpython-38.pyc  _envs.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/arch/arm64/boot/dts/xilinx$  cat /opt/pwndbg/.venv/lib/pyt
hon3.8/site-packages/pip/_internal/metadata/importlib/__pycache__/README-TRAPPED
Great sleuthing!
The next clue is in: /usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Asana-Math/Misc

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/arch/arm64/boot/dts/xilinx$ la -a
.                       zynqmp-zc1232-revA.dts       zynqmp-zc1751-xm018-dc4.dts  zynqmp-zcu104-revA.dts
..                      zynqmp-zc1254-revA.dts       zynqmp-zc1751-xm019-dc5.dts  zynqmp-zcu106-revA.dts
CLUE                    zynqmp-zc1275-revA.dts       zynqmp-zcu100-revC.dts       zynqmp-zcu111-revA.dts
Makefile                zynqmp-zc1751-xm015-dc1.dts  zynqmp-zcu102-rev1.0.dts     zynqmp.dtsi
avnet-ultra96-rev1.dts  zynqmp-zc1751-xm016-dc2.dts  zynqmp-zcu102-revA.dts
zynqmp-clk.dtsi         zynqmp-zc1751-xm017-dc3.dts  zynqmp-zcu102-revB.dts
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/arch/arm64/boot/dts/xilinx$ cd /usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Asana-Math/Misc
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Asana-Math/Misc$ ls -a
.  ..  .INFO  Regular
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Asana-Math/Misc$ cat .INFO
Great sleuthing!
The next clue is in: /usr/lib/python3/dist-packages/sympy/strategies

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Asana-Math/Misc$ cd /usr/lib/python3/dist-packages/sympy/strategies
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/sympy/strategies$ ls -a
.  ..  .TRACE  __init__.py  __pycache__  branch  core.py  rl.py  tests  tools.py  traverse.py  tree.py  util.py
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/sympy/strategies$ cat .TRACE
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{cZlpnm4J7m_Y1uYTT0yv5dljzMS.dljM4QDL2ETO0czW}
```
