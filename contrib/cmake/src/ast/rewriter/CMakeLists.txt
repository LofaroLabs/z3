z3_add_component(rewriter
  SOURCES
    arith_rewriter.cpp
    array_rewriter.cpp
    ast_counter.cpp
    bool_rewriter.cpp
    bv_bounds.cpp
    bv_rewriter.cpp
    datatype_rewriter.cpp
    der.cpp
    dl_rewriter.cpp
    enum2bv_rewriter.cpp
    expr_replacer.cpp
    expr_safe_replace.cpp
    factor_rewriter.cpp
    fpa_rewriter.cpp
    label_rewriter.cpp
    mk_simplified_app.cpp
    pb_rewriter.cpp
    pb2bv_rewriter.cpp
    quant_hoist.cpp
    rewriter.cpp
    seq_rewriter.cpp
    th_rewriter.cpp
    var_subst.cpp
    bv_trailing.cpp
    mk_extract_proc.cpp
  COMPONENT_DEPENDENCIES
    ast
    automata
    polynomial
  PYG_FILES
    arith_rewriter_params.pyg
    array_rewriter_params.pyg
    bool_rewriter_params.pyg
    bv_rewriter_params.pyg
    fpa_rewriter_params.pyg
    poly_rewriter_params.pyg
    rewriter_params.pyg
)
