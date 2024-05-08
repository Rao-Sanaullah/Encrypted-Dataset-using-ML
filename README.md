# Trade-offs-Between-Privacy-and-Performance-in-Encrypted-Dataset-using-Machine-Learning-Models


In recent years, with the increasing importance of dataset privacy in machine learning (ML) applications, there has been an increased demand for secure and privacy-preserving solutions. We present a comparative analysis of three well-known encryption methods applied to ML models: XOR encryption, substitution cipher, and homomorphic encryption. Therefore, we evaluate the performance of CNN models trained on encrypted datasets using these encryption techniques. We test the performance of CNN models trained on encrypted data with several encryption approaches. Parameters such as training time, memory usage, and classification accuracy are analyzed and compared between encryption methods. We also look into the effect of encryption on model interpretability and robustness against adversarial attacks. Furthermore, each trained model trains on an encrypted dataset used in real-time applications to explore the practical considerations and trade-offs associated with each encryption technique.

# Experimental Results:

\begin{table}[!t]
\footnotesize
\centering
\caption{Accuracy with Resource Consumption} \midrule
\label{tab:model}
{
\footnotesize
\begin{tabular}{cccccccc}
\toprule
\textbf{Encryption} & \textbf{Test} & \textbf{CPU Time} & \textbf{Memory} \\
\textbf{Model} & \textbf{Accuracy} & \textbf{(sec.)} & \textbf{(KB)} \\
\midrule
Original Data & 99.25\% & 85.50 & 306,140\\
XOR & 96.70\% & 76.61 & 156 \\
S.Cipher & 11.35\% & 75.92 & 30,744 \\
Homomorphic & 98.02\% & 75.92 & 30744\\
\bottomrule
\end{tabular}
}
\subfloat[\scriptsize Error Rate (\%)]{
\begin{tabular}{cc}
\toprule
\textbf{Encryption Techniques} & \textbf{Error Rate (\%)} \\
\midrule
Original Data & 0.75\% \\
XOR Encryption & 3.30\% \\
Substitution Cipher & 88.65\% \\
Homomorphic Encryption & 1.98\% \\
\bottomrule
\end{tabular}
}
\end{table}
