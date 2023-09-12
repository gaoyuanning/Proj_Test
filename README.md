# Proj_Test
1. Compile sqlite3 sources to get sqlite3 and memvfs
2. clang++ -std=c++11 -lproj -lsqlite3 -lpthread -ldl -lmemvfs proj_test.cpp proj_db.c -o proj_test
