### Adding to Ferrous

##Directory organization
- each component should have its own directory within `source/components/` named for the component
- each component directory should, at minimum, contain an index file and a main file
  - the index file should be located at `source/components/<component name>/_.scss` and should only include import statements for the other scss files in the directory
  - the main file should be located at `source/components/<component name>/component.scss` and should include the primary mixin for creating any version of the component
- each component may also have a file containing mixins to create specific versions of that component, at `source/components/<component name>/instances.scss`
- the rest of the scss files in the component directory (if necessary) should be broken out into sub-elements of the component, such as 'colors.scss', 'animations.scss', etc.
- javascripts, javascript specs, and svg markup that relate directly to a component should be included in the component directory
- for now, all ruby and rspecs are not located in `source/` (lib and spec, respectively)

## Writing specs
- our test suite currently uses rspec for all ruby code and jasmine for javascript code
- ALL RUBY AND JS that is to be included in the gem or npm package (ie. not the styleguide) should have full test coverage

## Styleguide and documentation
- Document all your components (there will be a description here regarding the best way to do that in the near future)
- No styleguide code shall live outside `source/styleguide` or `styleguide/`
- No code shall live in `source/styleguide` or `styleguide/` that is necessary for anything other than building the styleguide (all code necessary for maintaining the gem and npm packages should be independent of anything in those directories)

