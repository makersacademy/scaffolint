# ScaffoLint

The linter file that doesn't lead junior developers to bad habits.

Read [.rubocop.yml](.rubocop.yml) for details.

## Quickstart

1. Create a `.rubocop.yml` config file
    ```yaml
    # Configure Rubocop to use the config file in the Scaffolint GitHub repo
    inherit_from:
      - https://raw.githubusercontent.com/makersacademy/scaffolint/v1.1.0/.rubocop.yml
    ```
1. Add Rubocop to your `Gemfile`
    ```ruby
    group :development, :test do
      gem "rubocop", "0.79.0"
    end
    ```
1. Run `bundle install`
1. Run `rubocop`

## Editor integration

We recommend installing Rubocop support for your editor to get fast feedback as you write your code:

- Visual Studio Code: [ruby-rubocop extension](https://marketplace.visualstudio.com/items?itemName=misogi.ruby-rubocop)
- Atom: [linter-rubocop package](https://atom.io/packages/linter-rubocop)
