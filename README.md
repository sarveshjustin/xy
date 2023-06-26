# xy
```
module zap (x,y,z,w,f);
input x,y,z,w;
output f;
assign f = ((~y&z) | (x&y) | (y&w));
endmodule
```
