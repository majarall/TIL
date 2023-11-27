Type hints in python with the VScode extension 

1) Add in the settings.json the following lines:
    "python.analysis.inlayHints.functionReturnTypes": true,
    "python.analysis.inlayHints.variableTypes": true,

2) That`s it, pylance will now autocomplete with type hints

def array_op(a: np.array):
    return a.size

A = np.random.random((5,5))
print(array_op(A))
