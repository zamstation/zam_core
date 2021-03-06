# 0.7.0
- Feature: Default value for `stringify` in `ViewModel`.
- Feature: `NamedException.fromRaw` feature.
- Bugfix: SubscriptionManager function return types now inherit their parent.
- Dependency Updates:
	- `flutter 3.0.0` 
	- `dart 2.17.0` 
	- `meta 1.8.0` 
	- `rxdart 0.27.3` 
	- `lints 2.0.0` 
	- `test 1.21.1`

# 0.6.0
- Added `Model`.
- Added `Entity`.
- Added `UnknownException`.
- Added `Service`.
- Updated `ViewModel` with const constructor.
- Updated `ExceptionServerity` enum with a new value `fatal`.
- Dependency Updates: `meta 1.7.0`.

# 0.5.0
- **BREAKING:** Removed `NamedException` constructor.
- Updated `NamedException` with factory constructors.
- Added `BasicException`.
- Added `EmptyException`.
- Update dart sdk to 2.13.0.
- Added `Json` typedef for `Map<String, Object?>`.
- Update `Serialize`, `Deserialize`, `Serializable` with `Json`.
- Added `emptyCallback`.
- Added `emptyParameterizedCallback

# 0.4.0
- Added `ViewModel`.

# 0.3.0
- **BREAKING:** Removed `ObjectAsStreamExtension`.
- **BREAKING:** Removed `redux` library.
- Added `SubscriptionManager`.
- Added `rxdart` library.

# 0.2.0
- Added `equatable` library.
- Added `redux` library.
- Modified `zam_core.dart` to export all external libraries.

# 0.1.2
- Internal Repairs and Documentation.

# 0.1.1
- Modified `Builder`, `ParameterizedBuilder`, `Callback`, `ParameterizedCallback`, `ParameterizedVoidCallback`and `VoidCallback` so that their generics now allow nulls. For example, `Builder<INSTANCE extends Object?>` instead of `Builder<INSTANCE extends Object>`.

# 0.1.0
- Removed `BasicException` in favor of `NamedException`.
- Removed `EmptyException` in favor of `NamedException`.
- Modified `NamedException` to include features from `BasicException` and `EmptyException`.
- Modified order of generics in `ParameterizedBuilder` and `ParameterizedCallback`.
- Modified generics to extend either `Object` or `Object?` rather than `dynamic`.
- Modified generics to extend `Object?` instead of `Object` in `Executable` and `CallToExecute`.
- Added `meta` library to exports.
- Added `ExceptionBuilder` and `ParameterizedExceptionBuilder`
- Updated Tests.
- Updated Documentation.
- Updated Readme.

# 0.0.2
- Modified `Identifiable` with generic and mandatory key.
- Added more tests.
- Updated Documentation.
- Updated Example.

# 0.0.1
Released on **13-May-2021**

- Includes `Builder`, `ParameterizedBuilder`.
- Includes `Callback`, `ParameterizedCallback`, `ParameterizedVoidCallback`, `VoidCallback`.
- Includes `BasicException`, `EmptyException`, `ExceptionSeverity`, `NamedException`.  
- Includes `Activatable`, `AsyncDisposable`, `AsyncInitializable`, `AsyncInitializeWith`, `AsyncInitialize`, `AsyncLoadable`, `AsyncNestedInitializable`, `AsyncNestedInitialize`, `AsyncRunnable`, `AsyncStartable`, `AsyncStoppable`, `CallToExecute`, `Disposable`, `Executable`, `Initializable`, `InitializeWith`, `Initialize`, `Loadable`, `NestedInitializable`, `NestedInitialize`, `Runnable`, `Startable`, `Stoppable`, `Undoable`, `Validatable`.
- Includes `Categorizable`, `Cloneable`, `Copyable`, `Identifiable`, `ObjectAsStreamExtension`, `Parameterized`.
- Includes `Deserialize`, `Serializable`, `Serialize`.

