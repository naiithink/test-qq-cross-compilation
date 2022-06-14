# test-qq-cross-compilation

	hello*
	hello.asc
	hello.c
	hello.exe
	hello.exe.asc

---

	clang -target 'x86_64-pc-linux-gnu' hello.c -o hello
