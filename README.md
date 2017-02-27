# Xcode File Templates

Useful Xcode file templates for day to day use.

## Available templates

- **[Swift Test File](Swift Test File.xctemplate/XCTestCaseTabs/___FILEBASENAME___.swift)** containing:
	- `import XCTest`
	- `@testable import <project_name>`
	- Empty `setUp` and `tearDown` methods
	- Choose between tabs or spaces

- **[Swift Nimble Test file](Swift Nimble Test File.xctemplate/XCTestCaseTabs/___FILEBASENAME___.swift)** containing all of **Swift Test File** and:
	- An import for [Nimble](https://github.com/Quick/Nimble)

	
## Installation

1. Download/clone the repository

2. Create the templates directory if your don't have it:

	`mkdir -p ~/Library/Developer/Xcode/Templates/File\ Templates/Source`

2. Moved the templates (`.xctemplate` folders) you find useful to the templates directory, for example:

	`cp -r Swift\ Test\ File.xctemplate ~/Library/Developer/Xcode/Templates/File\ Templates/Source`
