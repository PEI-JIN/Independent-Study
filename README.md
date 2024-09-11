Summary:

低密度同位檢查碼 (LDPC Codes) 為錯誤更正碼的一種，用於更正資料在傳輸時受到通道雜訊干擾所造成的錯誤。由於 LDPC Codes 具有非常接近 Shannon 極限的卓越性能和保護大量資料傳輸之優勢，因此被 3GPP 採用作為 5G NR 標準中數據傳輸的編碼方式。本專案是使用 Column by Column 的平行處理方式，設計適用於 5G NR 標準的 LDPC Codes 解碼器。考量檢測矩陣中同一個 Row 之偏移值重複問題。藉由分配多組 Column Set 來避免資料存取衝突發生，並且提高平行處理速度，以滿足 5G 高速、低延遲的通訊要求。實驗數據顯示兩種矩陣針對不同 Zc 大小的平行化處理程度，首先 BG 1 在四種 Zc 的條件下進行 Column Set 分配，得知其平行解碼加速皆可提升為原本的三倍；而 BG 2 除了 Zc =128 外，其餘三種 Zc 的處理速度則加快二倍。未來希望能使用此解碼方式在非二元類循環 LDPC Codes 的解碼器。

Introduction Video:

https://youtu.be/yKR5yHhePKM
