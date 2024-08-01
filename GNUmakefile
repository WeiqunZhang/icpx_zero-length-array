CXX = icpx
CXXFLAGS = -O3 -std=c++17 -fsycl -Wpedantic -Werror

global_vars.o: global_vars.cpp
	$(CXX) $(CXXFLAGS) -c -o $@ $<

clean:
	${RM} *.o

FORCE:

.PHONY: clean
