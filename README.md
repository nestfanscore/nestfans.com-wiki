Nestfans.com::Wiki
--------------

Wiki 栏目插件 for [nestfans.com](https://github.com/nestfanscore/nestfans.com)

简单的实现 /wiki 栏目，并在导航栏显示。

## Usage

## Installation

在 nestfans.com 应用的 Gemfile 增加:

```ruby
gem 'nestfans.com-wiki'
```

And then execute:
```bash
$ bundle
```

## Configuration

修改 nestfans.com 的 `modules` 配置，增加 `wiki` 以启用。

```yml
defaults: &defaults
  # add "press" to modules
  modules: 'topic,...,wiki'
```

## License
The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
