# pagination
Contains pagination related structs, helpers, and constants.
`TotalPages` should always be used to calculate total pages based on total items and page size to make sure consistent behavior.
`StandardisePaginatedQuery` should be used to standardize pagination values. It makes sure that page size is one of the allowed sizes, and page number is not negative. `StandardPageSizes` and `ValidPageSizes` can also be used for validation.

###### Install
`go get github.com/blutspende/libs-pagination`