# selfについて

## self とは

selfはインスタンスオブジェクト自身を指しています。

クラスの中でインスタンスオブジェクトを呼び出す際やそのインスタンスオブジェクトを呼び出す際は、selfを使用します。

## self の使い方

以下では，self は name を表している

すなわち name がインスタンスオブジェクトを指している

```Ruby
class MyStr < String
  def show
    self.inspect
  end
end

name = MyStr("Alice")
name.show
=> "\"Alice\""
```