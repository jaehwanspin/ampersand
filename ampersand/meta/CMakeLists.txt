cmake_minimum_required(VERSION 3.12)

project    (ampersand.meta VERSION 0.1.0 LANGUAGES CXX)
add_library(ampersand.meta STATIC
            ../meta.hpp
            meta.hpp
            meta_object.hpp
            meta_script.hpp
            meta_function.hpp
            meta_impl.hpp
            attribute.hpp
            annotation.hpp
            verb.hpp
            operator.hpp
            operator_impl.hpp)

set_target_properties(ampersand.meta PROPERTIES LINKER_LANGUAGE CXX)