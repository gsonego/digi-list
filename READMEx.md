## Commands

`npm i @angular/cli -g`

`ng version`

`npm init`

`ng new digi-list`

`ng generate component <component_name>`

`ng g c <component_name>`


### Basic component

`
import { Component } from '@angular/core'


@Component({
	selector: 'hm-root',
	templateUrl: './app.component.html',
	styleUrls: [./app.component.css]  // must be an array
})
export class AppComponent {

	constructor() {
		
		// called once the component is initialized
		ngOnInit() {
		}		
	}
}
`