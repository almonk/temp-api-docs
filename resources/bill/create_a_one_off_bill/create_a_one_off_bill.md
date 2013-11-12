### Create a new one-off bill

A user pays a one-off amount to the merchant. The user will be asked for authorisation.

If the user has an existing active preauthorization, you may wish to [create a bill under a pre-authorization]()

#### Arguments

`amount`
:	_required_ the amount of the bill.

`name`
:	Brief description used to identify the payment, displayed to the user alongside the amount. Often useful for an invoice reference.

`description`
:	A more verbose description, which will be displayed to the user.

#### Returns

Returns a bill object.


