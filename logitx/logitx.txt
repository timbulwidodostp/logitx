# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Estimate an autoregressive logit model with covariates Use logitx With (in) R Software
install.packages("gets")
library("gets")
logitx = read.csv("https://raw.githubusercontent.com/timbulwidodostp/logitx/main/logitx/logitx.csv",sep = ";")
# Estimation Estimate an autoregressive logit model with covariates Use logitx With (in) R Software
y <- cbind(logitx$y)
x <- cbind(logitx$X1, logitx$X2, logitx$X3, logitx$X4, logitx$X5)
mymod1 <- logitx(y, ar=1)
mymod1
mymod2 <- logitx(y, ar=1:4)
mymod2
mymod3 <- logitx(y, ar=1:4, xreg=x)
mymod3
# Estimate an autoregressive logit model with covariates Use logitx With (in) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished