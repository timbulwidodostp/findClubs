# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finding (Finds) Convergence Clubs Use findClubs (ConvergenceClubs) With (In) R Software
install.packages("ConvergenceClubs")
library("ConvergenceClubs")
findClubs = read.csv("https://raw.githubusercontent.com/timbulwidodostp/findClubs/main/findClubs/findClubs.csv",sep = ";")
# Estimation Finding (Finds) Convergence Clubs Use findClubs (ConvergenceClubs) With (In) R Software
findClubs <- findClubs(findClubs,  dataCols=3:36, unit_names = 1, refCol=35, time_trim = 1/3, 
HACmethod = "FQSB", cstar = 0, cstar_method = 'incremental', cstar_increment = 0.1)
summary(findClubs)
# Finding (Finds) Convergence Clubs Use findClubs (ConvergenceClubs) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished