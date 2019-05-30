[Julia][julia]
[This](https://calculuswithjulia.github.io/getting-started-with-julia.html) has lots of good basic info on running IJulia

Docker has a julia build: `docker run -it --rm julia`

winOS Folder location: `C:\Users\Kris Johnson\AppData\Local\Julia-1.1.1`

CLI cmd:
`
Pkg.update()
Pk.add("PyCall")
Pkg.add("IJulia")
#then:
using IJulia
notebook()
`

[julia]: https://calculuswithjulia.github.io/ 'calculus'