# test-qq-cross-compilation

	hello*
	hello.asc
	hello.c

---

	clang -target 'x86_64-unknown-darwin-macho' hello.c -o hello
	clang -target 'aarch64-unknown-darwin-macho' hello.c -o hello
