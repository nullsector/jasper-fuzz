Fuzzing the JasPer Image Processing/Coding Tool Kit
  http://www.ece.uvic.ca/~mdadams/jasper
  https://github.com/mdadams/jasper

Found Null Pointer Dereference in jp2_encode (jp2_enc.c)
https://github.com/mdadams/jasper/issues/120

Usage: jasper --input [file] --output /dev/null --output-format jp2

Found with afl
http://lcamtuf.coredump.cx/afl/
