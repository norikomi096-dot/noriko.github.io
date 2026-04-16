# Hey
just a simple file test

simple python example
```python
def demo(arg: int) -> int:
  val: int = arg * arg
  return val

demo(20)
```

simple print using assembly for x86
```nasm
section .data
  msg: db "Hack all the things", 0x0a
  len: equ $ - msg

section .text
  global _start

_start:
  ; print
  mov eax, 4
  mov ebx, 1
  mov ecx, msg
  mov edx, len
  int 0x80

  ; exit
  mov eax, 1
  int 0x80
```

[click here](demo.html)

