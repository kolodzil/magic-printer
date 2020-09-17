# magic-printer - NodeJS
Create simple restfull service providing printing capabilities based on NodeJS (native, express... you can use all what you need)

You can print your text in different formats like `json`, `csv`, `html` and many others.

Printing can be ordered by sending correct request.
* POST `/magic-printer/print` -  is going to queue printing

To download ready document you need to hit.
* GET `/magic-printer/...`

To see queued documents
* GET `/magic-printer/...`

To cancel printing.
* ... `/magic-printer/...`
