# Make it more obvious that a PR is a work in progress and shouldn't be merged yet
warn("PR is classed as Work in Progress") if github.pr_title.include? "[WIP]"

# Warn when there is a big PR
warn("Big PR") if git.lines_of_code > 500

# Look for spelling issues
# prose.ignored_words = ["Nikita"]
# prose.check_spelling markdown_files

# Run SwiftLint
swiftlint.lint_files

message("Hello, this worked")