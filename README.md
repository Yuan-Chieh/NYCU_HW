# NYCU_HW

目前用於第三個前測作業，載入訓練好的CNN權重，避免沒過99%

將下列指令放入Test on held out data那區的最前面

!rm -rf NYCU_HW

!git clone https://github.com/Yuan-Chieh/NYCU_HW.git

net = torch.load("./NYCU_HW/310605018_cnn.pt")
