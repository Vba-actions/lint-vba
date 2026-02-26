# VBA Linter  
Ensure VBA code quality.

## Configuration

#### Options
| Name          	| Description                                 	| Optional 	| Default  	              |
|---------------	|---------------------------------------------	|----------	|-----------------------	|
| path          	| Path to source files.                       	| false    	| GITHUB_WORKSPACE      	|

## Example
```yaml  
 steps:
 - uses: actions/checkout@v3
 - name: Lint
   uses: Vba-actions/lint-vba@v1
   with:
     path: "src"
```
