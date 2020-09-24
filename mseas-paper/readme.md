### 院生時代の研究

[非圧縮性ナビエ–ストークス方程式](https://ja.wikipedia.org/wiki/%E3%83%8A%E3%83%93%E3%82%A8%E2%80%93%E3%82%B9%E3%83%88%E3%83%BC%E3%82%AF%E3%82%B9%E6%96%B9%E7%A8%8B%E5%BC%8F#%E4%B8%80%E8%88%AC%E8%A7%A3)を解くために、[射影法](https://ja.wikipedia.org/wiki/%E5%B0%84%E5%BD%B1%E6%B3%95)というアルゴリズムを使用することが多い。そのアルゴリズムは実際、[Richardson不動点反復法](https://en.wikipedia.org/wiki/Modified_Richardson_iteration)というアルゴリズムの特殊な場合である。射影法の場合は不動点反復法を繰り返せずに一度だけ適用される。数値解の精度を上げるためには、時間刻み幅（タイムステップ）を短縮することができるが、それより射影法を反復ほうが効率が高いと証明できる。
<br>
$$\begin{cases}
\frac{\partial \mathbf{u}}{\partial t}    =\nu \,\nabla^2 \mathbf{u} -  \mathbf{u} \cdot \nabla \mathbf{u} - \nabla p + \mathbf{f} \\
\nabla \cdot  \mathbf{u} = 0 \space (\text{非圧縮性条件}) \\
\end{cases}$$<center> **非圧縮性ナビエ–ストークス方程式 **</center>