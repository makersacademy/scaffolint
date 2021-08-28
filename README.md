# ScaffoLint

The linter file that doesn't lead junior developers to bad habits.

Read [.rubocop.yml](.rubocop.yml) for details.

## Quickstart

1. Add Rubocop to your `Gemfile`
    ```ruby
    group :development, :test do
      gem "rubocop", "1.20"
    end
    ```

2. Run `bundle install`

3. Copy the ScaffoLint config file to your project
    ```shell
    ; curl -o .rubocop.yml https://raw.githubusercontent.com/makersacademy/scaffolint/v2.0.0/.rubocop-stub.yml
    ```

    Or, if you already have a Rubocop config file, add the relevant lines from the [stub file](https://raw.githubusercontent.com/makersacademy/scaffolint/v2.0.0/.rubocop-stub.yml).

4. Gitignore the cached Rubocop file
  ```gitignore
  # File: .gitignore

  # Local cache of Rubocop remote config
  .rubocop-*
  ```

5. Run `rubocop`

## Editor integration

We recommend installing Rubocop support for your editor to get fast feedback as you write your code:

- Visual Studio Code: [ruby-rubocop extension](https://marketplace.visualstudio.com/items?itemName=misogi.ruby-rubocop)
- Atom: [linter-rubocop package](https://atom.io/packages/linter-rubocop)
