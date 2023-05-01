### 基础表格

```latex
\begin{table}[!htbp]
	\centering
	\setlength{\abovecaptionskip}{3pt}%caption与表格之间的距离
	\caption{缺失值检测}
	\label{t1}
	\resizebox{\textwidth}{!}{
		\begin{tabular}{cc}
			\toprule[1.5pt]
			\makebox[0.4\textwidth]{特证名} & \makebox[0.5\textwidth]{空值个数} \\
			\midrule
			文物编号 & 0 \\
			纹饰 & 0 \\
			类型 & 0 \\
			颜色 & 4 \\
			表面风化 & 0 \\
			\bottomrule[1.5pt]
		\end{tabular}
	}
\end{table}
```

### 基础图片

```latex
\begin{figure}[!htbp]
	\centering
	\includegraphics[width=0.6\textwidth]{组织结构图.png}
	\setlength{\abovecaptionskip}{3pt}%caption与表格之间的距离
	\caption{组织结构图}
	\label{p-1}
\end{figure}
```

### 并列子图

```tex
\begin{figure}[h]
	\centering
	\begin{minipage}[b]{0.3\linewidth}
		\includegraphics[width=1\textwidth]{s1.png}
	\end{minipage}
	\begin{minipage}[b]{0.3\linewidth}
		\includegraphics[width=1\textwidth]{s2.png}
	\end{minipage}
	\begin{minipage}[b]{0.3\linewidth}
		\includegraphics[width=1\textwidth]{s3.png}
	\end{minipage}
	\setlength{\abovecaptionskip}{3pt}%caption与表格之间的距离
	\caption{spearmand系数对比图}
\end{figure}
```

