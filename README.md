# zvm
A simple virtual machine written in ansii c, see wiki for more information.

<pre>
// compile and run a binary
as [assembly] [binary]
vm [binary]

// run in realtime mode
vm
</pre>

In realtime mode please only use int numbers

<pre>
  mov ax 0x7e3 (2019)
  mov bx 0x7c0 (1984)
  sub ax bx
  push ax
  print
</pre>

# In planning
 * Persistent storage
