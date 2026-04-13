# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Rank-based Estimates of Regression Coefficients Use rfit (Rfit) With (In) R Software
install.packages("Rfit")
library("Rfit")
# Estimation Rank-based Estimates of Regression Coefficients Use rfit (Rfit) With (In) R Software
rfit = read.csv("https://raw.githubusercontent.com/timbulwidodostp/rfit/main/rfit/rfit.csv",sep = ";")
rfit<-rfit(rfit ~ rfit_1 + rfit_2 + rfit_3, data = rfit)
summary(rfit)
# Rank-based Estimates of Regression Coefficients Use rfit (Rfit) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished