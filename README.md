# Generate a nest library 'common'

nest generate library common

# Generate a module 'database' inside a library 'common'

nest generate module database -p common

nest g app reservations

nest g resource reservations

# build docker image for reservations

$ cd apps/reservations/
$ docker build ../../ -f Dockerfile -t sleepr_reservations

# run docker image for reservatoins

$ docker run sleepr_reservations
