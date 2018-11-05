PN2的解析实现

target/in progress：python

target.todo：rust, elixir, F#, typescript/haxe, java/scala/kotlin

PN2语法借鉴：APL/K/Q、Forth、erlang


for example/1：
>code main.c`rs
```
rs)
main ->
 `print "hello"
```
>elixir c8/comp.exs main.c`rs
```rust
fn main(){
  print!("hello");
}
```

例2：
>code 测试1.c8
```
c8>
main ->
 输出 hello

> f=c8/main, o=main.*
> biu = f->o

py)+
print 'done'

> biu: rs ex py
```
>elixir c8/comp.exs 测试1.c8 ; main.py
```
def main():
  print('hello')

def add():
  print('done')
if __name__ == '__main__':
  main(); add()
```
main.ex, main.rs与之类似


roadmap
-------
 
 - py web框架/django/pyramid; 必要+充分
 - py爬虫
 - elixir
 - rust
 - ...
 - PN2.todo: prolog的回溯和unification
