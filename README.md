# 112-2_ADSP_NTU_2024Spring_Advanced-Digital-Signal-Processing
112-2_丁建均_高等數位訊號處理_ADSP_NTU_2024Sring_Advanced Digital Signal Processing

## HW1 — Parks-McClellan FIR 濾波器設計
- 以迭代方式實作 Remez Exchange 演算法，設計一個 17 階低通 FIR 濾波器（通帶 0–1200 Hz、截止帶 1500–3000 Hz），並繪製頻率響應與脈衝響應圖

## HW2 — Hilbert Transform 濾波器設計
- 以 IDFT 方法設計 Hilbert Transform FIR 濾波器，手動加入過渡帶後計算脈衝響應 r[n]，並與理想頻率響應比較

## HW3 — YCbCr 色彩子採樣（4:2:0）
- 將輸入影像從 BGR 轉換至 YCbCr 色彩空間，對色度通道（Cr、Cb）執行 4:2:0 子採樣後再升採樣還原，比較壓縮前後的視覺差異

## HW4 — 影像品質評估（SSIM）
- 計算兩張灰階影像之間的結構相似度指標（SSIM），並印出各自的平均值、變異數與相關係數，同時將兩張影像並排顯示

## HW5 — 雙實數序列的 FFT 同時計算
- 利用一次 FFT 同時求得兩個實數序列 x[n] 與 y[n] 的 DFT，方法是將兩者分別作為複數的實部與虛部合併運算，再透過對稱性拆分還原 Fx 與 Fy
