# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Maximum likelihood estimation of copula-based bivariate zero-inflated (and non-inflated) count models Use bizicount With (In) R Software
install.packages("bizicount")
library("bizicount")
# Estimate Maximum likelihood estimation of copula-based bivariate zero-inflated (and non-inflated) count models Use bizicount With (In) R Software
bizicount = read.csv("https://raw.githubusercontent.com/timbulwidodostp/bizicount/main/bizicount/bizicount.csv", sep = ";")
f1 = y1 ~ X1.1 + X1.2 | Z1.1 + Z1.2
f2 = y2 ~ X2.1 + X2.2 | Z2.1 + Z2.2
bizicount = bizicount(f1, f2, bizicount, cop = "g", margins = c("zinb", "zip"), keep = TRUE)
summary(bizicount)
# Maximum likelihood estimation of copula-based bivariate zero-inflated (and non-inflated) count models Use bizicount With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished