set(wxml_src
    flib_wxml.f90
    m_wxml_buffer.f90
    m_wxml_core.f90
    m_wxml_dictionary.f90
    m_wxml_elstack.f90
    m_wxml_text.f90
    )
add_library(wxml ${wxml_src})
