# Pascal-P5
Pascal-P5 v1.3 / 1.4 for Delphi.

![image](https://user-images.githubusercontent.com/14885863/149734940-da303252-b089-4ee0-a337-8d3fa69633ee.png)
![image](https://user-images.githubusercontent.com/14885863/149663300-e320f4ce-f4ba-45bc-9771-1442c391f140.png)
![image](https://user-images.githubusercontent.com/14885863/150458903-113e6f5b-42ee-4a42-bff3-a5806e42b7fe.png)

Original version is here:

 - [pascal-p5 (sourceforge.net)](https://sourceforge.net/projects/pascalp5/)

## External file enhancement

```pascal
program Test(input, output, TMP='TEMP.TXT');
var
  TMP: text;
begin
  Writeln('Hello, world.');
  Rewrite(TMP);
  Writeln(TMP, 'Hello, world.');
end.
```

## Command-line parameter enhancement

```
PCOM <Pascal file (*.pas)>
PINT <Intermediate file (*.p5)>
```
