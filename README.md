vader.vim
=========

```
# Test case
Execute (test vision#assertion):
  Assert vader#assert#true('hey' == 'hey')
  Assert vader#assert#equal('hey', 'hey')
  Assert 1 == 1
  AssertEqual 'hey', 'h'.'e'.'y'

Given ruby (some ruby code):
  def a
    a = 1
    end

Do (indenting the block):
  vip
  =

Expect ruby:
  def a
    a = 1
  end

Do:
  vip
  =
  gv
  >

Expect ruby (indented):
    def a
      a = 1
    end
```