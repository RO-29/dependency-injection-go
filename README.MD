# Dependency Injection in GO

## GO Dependency injection Example output

    ➜ go run main.go

    ** Init DIprovider A **<
    ** Init serviceA **
    ** Init DIprovider B **
    ** Init serviceB **
    from A:
    hey there:  testing
    ** Init DIprovider C **
    ** Init serviceC **
    ** Using already init DIprovider B **
    from C:
    hey there:  testing
