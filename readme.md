# Guidelines for flutter development.

Set of architecture, code styling, project setup, different logic and ui implementation rules.
To mock data use fake datasource

## Table of Contents

## Project setup
 ### File Structure:
 ```
assets/
	images/
		logo.png
	fonts/
		Roboto.org
lib/
	ui/
		screens/
			login/
				login_screen.dart
				login_view_model.dart
				login_router.dart
				login_repository.dart		
				custom/
		shared/
	data/
		model/
			user.dart
		color.dart
		style.dart
		constants.dart
	utils/
		helper.dart
	service/
		api.dart
	main.dart
	injector.dart
	navigator.dart
```

## Naming
### Methods
`"fetch"` for network requests. example: `fetchUsers`.

`"retrieve"` for getting data from local base. example: `retrieveUsers`.
### Class name
`"screen"` as suffix for widgets that represents separate screen or page. example: `LoginScreen`.
## Architecture
To mock data use fake datasource
