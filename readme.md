# Guidelines for flutter development.

Set of architecture, code styling, project setup, different logic and ui implementation rules.


## Table of Contents

## Project setup
 ### File Structure:
 ```
assets/
	images/
		logo.png
lib/
	scene/
		login/
			login_screen.dart
			login_view_model.dart
			login_router.dart
			login_repository.dart		
			view/
		shared/
	data/
		model/
			user.dart
		color.dart
		style.dart
		constants.dart
	utility/
		helper.dart
	service/
		api.dart
	main.dart
	injector.dart
```

## Naming
   ### Methods:
	"fetch" for network requests
	"retrieve" for getting data from local base
	"page" as suffix for widgets that represents separate screen or page
