
|IEC 61850 Type         | IEC 61499 Data Type         | Remark                              |
|-----------------------|-----------------------------|-------------------------------------|
| BOOLEAN               | DirectlyDerivedType(BOOL)   |                                     |
| INT8                  | DirectlyDerivedType(SINT)   |                                     |
| INT16                 | DirectlyDerivedType(INT)    |                                     |
| INT32                 | DirectlyDerivedType(DINT)   |                                     |
| INT64                 | DirectlyDerivedType(LINT)   |                                     |
| FLOAT32               | DirectlyDerivedType(REAL)   |                                     |
| INT8U                 | DirectlyDerivedType(USINT)  |                                     |
| INT16U                | DirectlyDerivedType(UINT)   |                                     |
| INT24U                | SubrangeType(UDINT)         | LowerLimit: 0, UpperLimit: 2^{24}-1 |
| INT32U                | DirectlyDerivedType(UDINT)  |                                     |
| ENUMERATED            | EnumeratedType              |                                     |
| CODED ENUM            | EnumeratedType              |                                     |
| OCTED STRING          | DirectlyDerivedType(STRING) | Including length                    |
| VISIBLE STRING        | DirectlyDerivedType(STRING) | Including length                    |
| UNICODE STRING        | DirectlyDerivedType(STRING) | Including length                    |
| ARRAY                 | ArrayType                   |                                     |
| PACKED LIST           | StructuredType              |                                     |
| Other composed types  | StructuredType              |                                     |
