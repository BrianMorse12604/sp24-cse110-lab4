1. Line 9 prints: "values added: 20"
2. Line 13 prints: "final result: 20"
3. Line 9 prints: "values added: 20"
4. Line 13 returns an error since result is no longer accessible since its scope was only within the if block, so when it is referred to out of that block, there is no defined variable named result
5. Nothing is printed in line 9 since an error is thrown in line 7 as we try to reassign a constant variable, which is not allowed
6. Nothing is printed in line 13 since an error is thrown in line 7 as we try to reassign a constant variable, which is not allowed