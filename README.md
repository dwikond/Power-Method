# Power-Method
#Dwiko Nugroho Dani (17523115)
#Rio Galang Jati R (17523118)

#find dominant eigenvalue matrix P

P <- matrix(c(0 ,11, −5, −2, 1, −7, −4, 26,−10), 3, 3, TRUE)

Y_eigen <- eigen(P)

Y_eigen$values[1]

#find corresponding eigenvector matrix P

X <- Y_eigen$vectors[,1]/sum(Y_eigen$vectors[,1])
