# ScaffoLint

The linter file that doesn't lead junior developers to bad habits.

Read [.rubocop.yml](.rubocop.yml) for details.

## Quickstart

1. Copy `.rubocop.yml` into the root of your project.
1. Add Rubocop to your `Gemfile`
    ```ruby
    group :development, :test do
      gem "rubocop", "0.79.0"
    end
    ```
1. Run `bundle install`
1. Run `rubocop`
