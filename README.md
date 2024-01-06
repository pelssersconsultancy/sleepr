# Generate a nest library 'common'

nest generate library common

# Generate a module 'database' inside a library 'common'

nest generate module database -p common

nest g app reservations

nest g resource reservations
