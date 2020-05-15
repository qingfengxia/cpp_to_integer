[![Build Status](https://travis-ci.org/qingfengxia/cpp_to_integer.svg?branch=master)](https://travis-ci.org/qingfengxia/cpp_to_integer.svg)   [![Windows Build status](https://ci.appveyor.com/api/projects/status/lkpn62t55wfie52t?svg=true)](https://ci.appveyor.com/project/qingfengxia/cpp-to-integer)


[![Boost Software License][license-badge]](LICENSE.txt)

# Development and demonstration of some cpp proposals

This repository holds code demonstration related safe numerics

### Download the header-only library and use it in your project

[Boost Software License](https://www.boost.org/users/license.html). It is free for open source and close source project.


## Proposals
### Runtime safe `numeric_cast`

[proposal: numeric_cast](proposal_numeric_cast.md)

### Reuse keyword `explicit` to prevent implicit conversion of function parameter

[proposal: Reuse keyword `explicit` to prevent implicit conversion of function parameter](proposal_explicit.md)

### Consistent runtime safe indexing for STL containers

 `std::get<index_value>(ContainerType c)` for `std::vector<>`
[Proposal: runtime safe getter](proposal_safe_get.md)

===

## Demonstration of safe numeric and performance hit

### Big float and big integer


### checked integral arithmetic


### floating point exception


## Misc
### Demonstration of `has_member()` type trait

It has already in C++20, here there is a demo to use them, and also collected solution from Stackoverflow, to implement in C++03, C++11.