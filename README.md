# test-qq-cross-compilation

	hello*
	hello.asc
	hello.c
	hello.exe
	hello.exe.asc

---

	clang -target 'x86_64-unknown-none-gnu' hello.c -o hello
