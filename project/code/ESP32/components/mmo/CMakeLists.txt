set(COMPONENT_ADD_INCLUDEDIRS "include" 
                              "test" 
                              "test/unity")
set(COMPONENT_PRIV_INCLUDEDIRS "include" 
                               "test" 
                               "test/unity")
set(COMPONENT_SRCS "matrix_add.c" 
                   "matrix_inv.c" 
                   "matrix_mul.c" 
                   "matrix_sub.c" 
                   "matrix.c" 
                   "test/matrix_add_test.c" 
                   "test/matrix_inv_test.c" 
                   "test/matrix_mul_test.c" 
                   "test/matrix_sub_test.c" 
                   "test/matrix_test.c" 
                   "test/unity/unity.c")

register_component()

