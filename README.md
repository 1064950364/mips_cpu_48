# mips_cpu_48
mips5级流水线cpu,支持48条指令间转发与暂停，工程化方法进行覆盖性分析
1、支持mips5级流水线48条指令：
MIPS-C3指令集（去掉MTHI,MTLO指令，共48条）
LB、LBU、LH、LHU、LW、SB、SH、SW、ADD、ADDU、SUB、SUBU、MULT、MULTU、DIV、DIVU、
SLL、SRL、SRA、SLLV、SRLV、SRAV、AND、OR、XOR、NOR、ADDI、ADDIU、ANDI、ORI、XORI、
LUI、SLT、SLTI、SLTIU、SLTU、BEQ、BNE、BLEZ、BGTZ、BLTZ、BGEZ、J、JAL、JALR、JR、
MFHI、MFLO 
2、乘除与加减运算时间相同，没有故意延迟。
3、采用工程化方法，进行覆盖性分析
   支持48条指令间所有的转发和暂停
4、mars导出的十六进制代码放在code.txt
5、感谢北航高小鹏老师与南航冯爱民老师的指导
