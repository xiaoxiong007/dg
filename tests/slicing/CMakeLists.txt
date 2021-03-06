# Debug runner will print output when a test fails
set(RUNNER "${CMAKE_SOURCE_DIR}/tests/slicing/test-runner-debug.py")

add_test(test1                  ${RUNNER} test1)
add_test(test2                  ${RUNNER} test2)
add_test(test3                  ${RUNNER} test3)
add_test(test4                  ${RUNNER} test4)
add_test(test5                  ${RUNNER} test5)
add_test(test6                  ${RUNNER} test6)
add_test(test7                  ${RUNNER} test7)
add_test(test8                  ${RUNNER} test8)
add_test(test22                 ${RUNNER} test22)
add_test(test222                ${RUNNER} test222)
add_test(recursive1             ${RUNNER} recursive1)
add_test(recursive2             ${RUNNER} recursive2)
add_test(recursive3             ${RUNNER} recursive3)
add_test(recursive4             ${RUNNER} recursive4)
add_test(recursive5             ${RUNNER} recursive5)
add_test(interprocedural1       ${RUNNER} interprocedural1)
add_test(interprocedural2       ${RUNNER} interprocedural2)
add_test(interprocedural3       ${RUNNER} interprocedural3)
add_test(interprocedural4       ${RUNNER} interprocedural4)
add_test(interprocedural5       ${RUNNER} interprocedural5)
add_test(interprocedural6       ${RUNNER} interprocedural6)
add_test(interprocedural7       ${RUNNER} interprocedural7)
add_test(interprocedural8       ${RUNNER} interprocedural8)
add_test(interprocedural9       ${RUNNER} interprocedural9)
add_test(funcptr1               ${RUNNER} funcptr1)
add_test(funcptr2               ${RUNNER} funcptr2)
add_test(funcptr3               ${RUNNER} funcptr3)
add_test(funcptr4               ${RUNNER} funcptr4)
add_test(funcptr5               ${RUNNER} funcptr5)
add_test(funcptr6               ${RUNNER} funcptr6)
add_test(funcptr7               ${RUNNER} funcptr7)
add_test(funcptr8               ${RUNNER} funcptr8)
add_test(funcptr9               ${RUNNER} funcptr9)
add_test(funcptr10              ${RUNNER} funcptr10)
add_test(funcptr11              ${RUNNER} funcptr11)
add_test(funcptr12              ${RUNNER} funcptr12)
add_test(funcptr13              ${RUNNER} funcptr13)
add_test(funcptr14              ${RUNNER} funcptr14)
add_test(funcptr15              ${RUNNER} funcptr15)
add_test(funcptr16              ${RUNNER} funcptr16)
add_test(funcptr-regression1    ${RUNNER} funcptr-regression1)
add_test(funcarray1             ${RUNNER} funcarray1)
add_test(funcarray2             ${RUNNER} funcarray2)
add_test(funcarray3             ${RUNNER} funcarray3)
add_test(unknownptr1            ${RUNNER} unknownptr1)
add_test(unknownptr2            ${RUNNER} unknownptr2)
add_test(unknownptr3            ${RUNNER} unknownptr3)
add_test(unknownptr4            ${RUNNER} unknownptr4)
add_test(unknownptr5            ${RUNNER} unknownptr5)
add_test(unknownptr6            ${RUNNER} unknownptr6)
add_test(unknownptr7            ${RUNNER} unknownptr7)
add_test(unknownptr8            ${RUNNER} unknownptr8)
add_test(unknownptr9            ${RUNNER} unknownptr9)
add_test(unknownptr10           ${RUNNER} unknownptr10)
add_test(unknownptr11           ${RUNNER} unknownptr11)
add_test(pointers1              ${RUNNER} pointers1)
add_test(pointers2              ${RUNNER} pointers2)
add_test(pointers3              ${RUNNER} pointers3)
add_test(pointers4              ${RUNNER} pointers4)
add_test(pointers5              ${RUNNER} pointers5)
add_test(pointers6              ${RUNNER} pointers6)
add_test(pointers7              ${RUNNER} pointers7)
add_test(ptrarray1              ${RUNNER} ptrarray1)
add_test(ptrarray2              ${RUNNER} ptrarray2)
add_test(phi1                   ${RUNNER} phi1)
add_test(phi2                   ${RUNNER} phi2)
add_test(phi3                   ${RUNNER} phi3)
add_test(phi4                   ${RUNNER} phi4)
add_test(phi1-nophi             ${RUNNER} phi1-nophi)
add_test(phi2-nophi             ${RUNNER} phi2-nophi)
add_test(phi3-nophi             ${RUNNER} phi3-nophi)
add_test(phi4-nophi             ${RUNNER} phi4-nophi)
add_test(global1                ${RUNNER} global1)
add_test(global2                ${RUNNER} global2)
add_test(global3                ${RUNNER} global3)
add_test(global4                ${RUNNER} global4)
add_test(global5                ${RUNNER} global5)
add_test(global6                ${RUNNER} global6)
add_test(global7                ${RUNNER} global7)
add_test(global8                ${RUNNER} global8)
add_test(global9                ${RUNNER} global9)
add_test(global10               ${RUNNER} global10)
add_test(ptrtoint1              ${RUNNER} ptrtoint1)
add_test(ptrtoint2              ${RUNNER} ptrtoint2)
add_test(ptrtoint3              ${RUNNER} ptrtoint3)
add_test(ptrtoint4              ${RUNNER} ptrtoint4)
add_test(ptrtoint5              ${RUNNER} ptrtoint5)
add_test(ptrtoint6              ${RUNNER} ptrtoint6)
add_test(ptrtoint7              ${RUNNER} ptrtoint7)
add_test(llvmmemcpy             ${RUNNER} llvmmemcpy)
add_test(llvmmemcpy2            ${RUNNER} llvmmemcpy2)
add_test(memset1                ${RUNNER} memset1)
add_test(memcpy1                ${RUNNER} memcpy1)
add_test(memcpy2                ${RUNNER} memcpy2)
add_test(memcpy3                ${RUNNER} memcpy3)
add_test(memcpy4                ${RUNNER} memcpy4)
add_test(memcpy5                ${RUNNER} memcpy5)
add_test(memcpy6                ${RUNNER} memcpy6)
add_test(bitcast1               ${RUNNER} bitcast1)
add_test(bitcast2               ${RUNNER} bitcast2)
add_test(bitcast3               ${RUNNER} bitcast3)
add_test(bitcast4               ${RUNNER} bitcast4)
add_test(bitcast5               ${RUNNER} bitcast5)
add_test(loop1                  ${RUNNER} loop1)
add_test(loop2                  ${RUNNER} loop2)
add_test(loop3                  ${RUNNER} loop3)
add_test(loop4                  ${RUNNER} loop4)
add_test(loop5                  ${RUNNER} loop5)
add_test(list1                  ${RUNNER} list1)
add_test(list2                  ${RUNNER} list2)
add_test(list3                  ${RUNNER} list3)
add_test(list4                  ${RUNNER} list4)
add_test(list5                  ${RUNNER} list5)
add_test(list6                  ${RUNNER} list6)
add_test(list7                  ${RUNNER} list7)
add_test(list8                  ${RUNNER} list8)
add_test(list9                  ${RUNNER} list9)
add_test(dynalloc1              ${RUNNER} dynalloc1)
add_test(dynalloc2              ${RUNNER} dynalloc2)
add_test(dynalloc3              ${RUNNER} dynalloc3)
add_test(dynalloc4              ${RUNNER} dynalloc4)
add_test(dynalloc5              ${RUNNER} dynalloc5)
add_test(dynalloc6              ${RUNNER} dynalloc6)
add_test(dynalloc7              ${RUNNER} dynalloc7)
add_test(realloc1               ${RUNNER} realloc1)
add_test(realloc2               ${RUNNER} realloc2)
add_test(cyclic-realloc         ${RUNNER} cyclic-realloc)
add_test(switch1                ${RUNNER} switch1)
add_test(switch2                ${RUNNER} switch2)
add_test(vararg1                ${RUNNER} vararg1)
add_test(vararg2                ${RUNNER} vararg2)
add_test(vararg3                ${RUNNER} vararg3)
add_test(vararg4                ${RUNNER} vararg4)
add_test(negoffset1             ${RUNNER} negoffset1)
add_test(negoffset2             ${RUNNER} negoffset2)
add_test(negoffset3             ${RUNNER} negoffset3)
add_test(sum1                   ${RUNNER} sum1)
add_test(sum2                   ${RUNNER} sum2)
add_test(sum3                   ${RUNNER} sum3)
add_test(control-regression1    ${RUNNER} control-regression1)
add_test(pta_fs_regression1     ${RUNNER} pta_fs_regression1)
add_test(pta_fs_regression2     ${RUNNER} pta_fs_regression2)
add_test(pta_regression2        ${RUNNER} pta_regression2)
add_test(pta_regression3        ${RUNNER} pta_regression3)
add_test(alias_of_return        ${RUNNER} alias_of_return)
add_test(regression1            ${RUNNER} regression1)
add_test(fptoui                 ${RUNNER} fptoui)
add_test(malloc-redef           ${RUNNER} malloc-redef)
add_test(globalptr1             ${RUNNER} globalptr1)
add_test(globalptr2             ${RUNNER} globalptr2)
add_test(globalptr3             ${RUNNER} globalptr3)
add_test(globalptr4             ${RUNNER} globalptr4)
# Disabled until we properly support threads again
# add_test(threads1               ${RUNNER} threads1)
add_test(pta-inv-infinite-loop  ${RUNNER} pta-inv-infinite-loop)
add_test(undefcall1             ${RUNNER} undefcall1)
add_test(undefcall2             ${RUNNER} undefcall2)
add_test(unknown-interproc      ${RUNNER} unknown-interproc)
add_test(unknown-interproc2     ${RUNNER} unknown-interproc2)
add_test(unknown-interproc2-a   ${RUNNER} unknown-interproc2-a)
add_test(unknown-interproc3     ${RUNNER} unknown-interproc3)
add_test(atomic1                 ${RUNNER} atomic1)
add_test(atomic2                 ${RUNNER} atomic2)
add_test(atomic3                 ${RUNNER} atomic3)

