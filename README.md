# only_diff

`only_diff` is a tool that allows you to execute specific commands only on modified files. This helps optimize execution time and focus on the relevant parts of the code.

## Installation

To install `only_diff`, follow the steps below:

1. Download or clone the repository to your machine.
2. Open the terminal and navigate to the directory where you downloaded/cloned the repository.
3. Run the following commands:

```bash
chmod +x only_diff
sudo cp only_diff /usr/local/bin/only_diff
```

This will ensure that the `only_diff` script is executable and copy it to the `/usr/local/bin` directory, allowing you to run it from anywhere in the system.

## Usage

`only_diff` can be used to execute specific commands on modified files. Here are some examples of how to use it:

- To list all modified files, run the following command:

```bash
only_diff files_changed
```

This will display a list of all files that have been modified.

- To run RSpec only on modified files, use the following command:

```bash
only_diff rspec
```

This will run RSpec only on the files that have been modified since the last commit.

- To run `bundle exec m` only on modified files, execute the following command:

```bash
only_diff mini_test
```

This will run `bundle exec m` only on the modified files.

- To run RuboCop only on modified files, use the following command:

```bash
only_diff rubocop
```

This will run RuboCop only on the modified files.

Make sure you are in the correct project directory when running these commands.
