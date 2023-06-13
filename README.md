# Peanut-dataset
Dataset for plant segmentation

The Peanut dataset was collected from peanut fields near Danang in Vietnam. The dataset contains peanut plants and different weeds such as goose grass, nut grass. Peanut plants are referred as the crop class while all types of weeds are grouped into the weed class. Our dataset consists of 400 color images of the size $720 \times 960$. The dataset contains many challenging cases where crops and weeds appear in different sizes and inter-plant overlap. Specifically, a substantial amount of weeds have significantly small size that represents a difficult condition for the segmentation task.

The color map: Green - Crop, Red - Weed, Black - Background.

\begin{table}
\centering
\caption{The distribution of class labels in the Peanute dataset. BG stands for background.}
\begin{tabular}{|c|c|c|ccc|}
\hline
\multirow{2}{*}{Dataset} & \multirow{2}{*}{Images} & \multirow{2}{*}{Resolution} & \multicolumn{3}{c|}{Number of pixels ($\times 10^6$)}                                           \\ \cline{4-6} 
                         &     &                             & \multicolumn{1}{c|}{Crop}       & \multicolumn{1}{c|}{Weed}       & BG  \\ \hline
Peanut                   & 400       & 720 x 960                   & \multicolumn{1}{c|}{33.9} & \multicolumn{1}{c|}{9.6}  & 233.7 \\ \hline
\end{tabular}
\end{table}

This datasets are released under the Creative Commons license CC BY-SA 4.0

Copyright (c) 2023 Phan Tran Dang Khoa



