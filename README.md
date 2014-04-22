Bookstore
=========
The assignment for this project is to create a XSD which will validate XML
Documents that contain information about a bookshop. The bookshop has
two main departments “scientific products” and “leisure products”.

XSD Creation
The root element in our XSD it the element “bookshop”. We are using two
namespaces in order to differentiate the science products department and
the leisure products department.
The science department contains of books
and journals, and they can appear in the document zero or more times.
Also we take into account the fields that are required and the optional
ones.
Hence book in the science department and book in leisure products are
same type, they differentiate because they are in different namespaces.
For the “genre” attribute, we are using enumeration to make the restriction
of limited possibilities the bookstore has.
For elements that can only be present one at a time, like for example
authors and editors for the book, we use choice indicator.
For the price and the impact factor value element we are using decimals.
For the string values like title, author, editor, publisher, abstract, edition we
are applying the preserve whitespace restriction. Positive integer for
volume, number, start page, end page.
