# cobra-bignum
Polymer element to display big numbers in a human readable format

# cobra-bignum
Polymer element to display big numbers in a human readable format
## Installation
bower install cobra-bignum --save
## Usage
The attribute bignum is the input for the number that should be displayed.
Attribute language can be set to en, de or pt.

If the value of bignum is below 1 Million the unchanged value will be displayed.
Higher numbers will displayed in a shortened format.

Eg:

<cobra-bignum bignum="1230000" language="en"/>

will display: "1.2 Million"


## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
## History


## License
MIT