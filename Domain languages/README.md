##SMILES
SMILES（Simplified molecular input line entry specification），简化分子线性输入规范，是一种用ASCII字符串明确描述分子结构的规范。SMILES由Arthur Weininger和David Weininger于20世纪80年代晚期开发，并由其他人，尤其是日光化学信息系统有限公司（Daylight Chemical Information Systems Inc.），修改和扩展。
由于SMILES用一串字符来描述一个三维化学结构，它必然要将化学结构转化成一个生成树，此系统采用纵向优先遍历树算法。转化时，先要去掉氢，还要把环打开。表示时，被拆掉的键端的原子要用数字标记，支链写在小括号里。
SMILES字符串可以被大多数分子编辑软件导入并转换成二维图形或分子的三维模型。转换成二维图形可以使用Helson的“结构图生成算法”（Structure Diagram Generation algorithms）。