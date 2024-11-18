# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Estimates gravity models via double demeaning (DDM) the left hand side and right hand side of the gravity equation Use ddm (gravity) With (In) R Software
install.packages("gravity")
library("gravity")
DDM = read.csv("https://raw.githubusercontent.com/timbulwidodostp/DDM/main/DDM/DDM.csv",sep = ";")
# (Estimation) Estimates gravity models via double demeaning (DDM) the left hand side and right hand side of the gravity equation Use ddm (gravity) With (In) R Software
DDM<-ddm(dependent_variable="flow",distance="distw",additional_regressors=c("rta","comcur","contig"),code_origin="iso_o",code_destination="iso_d",data= DDM)
summary(DDM)
# Estimates gravity models via double demeaning (DDM) the left hand side and right hand side of the gravity equation Use ddm (gravity) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished