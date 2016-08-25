Credit Card Form
=========

This component is used to display a credit card form.

#### How to use:

```js
import CreditCardForm from 'blocks/credit-card-form';

render() {
	return (
		<CreditCardForm
            initialValues={ {} }
            recordFormSubmitEvent={ noop }
            saveStoredCard={ () => Promise.reject( { message: 'This is only example' } ) }
            successCallback={ noop } />
	);
}
```

#### Props

* `initialValues`: TBD.
* `recordFormSubmitEvent`: TBD.
* `saveStoredCard`: TBD.
* `successCallback`: TBD.
