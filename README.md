var i,j:integer;
a: array [1..5,1..5]of integer;
begin
for i:=1 to 5 do 
for j:=1 to 5 do
a[i,j]:=random(10);
for i:=1 to 5 do 
begin
for j:=1 to 5 do
write(a[i,j]:3);
writeln;
end;
end.

