*Minimal examples:*
```cpp
#include <iostream>
#include "vec2.hpp"

vec2<int> a{4, 2}, b{5, 1}, c = a + b;

int main(){
	std::cout << c.x << ", " << c.y << std::endl; // 9, 3
}
```

```cpp
#include <iostream>
#include "vec3.hpp"

vec3<float> a{7.0f, 1.5f, 2.5f}, b{3.0f, 4.0f, 5.0f}, c = a + b;

int main(){
	std::cout << c.x << ", " << c.y << ", " << c.z << std::endl; // 10, 5.5, 7.5
}
```
