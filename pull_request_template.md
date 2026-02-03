## Summary
- What does this PR change?

## Type of change
- [ ] Bug fix
- [ ] New feature
- [ ] Refactor / cleanup
- [ ] Build / CI
- [ ] Docs

## Related issues
Fixes #NNN

## Build & Test
**Toolchain:** GCC/Clang/MSVC (version), C++ standard  
**Build system:** CMake/Meson/Bazel (version)  
**Commands used:**
```bash
cmake -S . -B build -DCMAKE_BUILD_TYPE=Release ...
cmake --build build -j
ctest --test-dir build --output-on-failure
