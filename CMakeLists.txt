SET(BASE32_SOURCES    
    Base32.cpp
)


# Add library crossguid
# ---------------------------

add_library(base32 ${CROSSGUID_SOURCES})

