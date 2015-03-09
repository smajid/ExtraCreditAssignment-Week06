
Examples of any() and all()
===========================

    The question asked for a *working* example, so I have kept it simple. 
    Just type up the following commands on the VM terminal to confirm 
    if you get similar results, then try various options and combinations 
    to see how these functions work.

.. code :: python

    >>> list_1 = ['Hello', False, 1, 4.5]

    >>> any(list_1)
    True

    >>> all(list_1)
    False

    
.. code :: python

    >>> list_2 = []

    >>> any(list_2)
    False

    >>> all(list_2)
    True


Examples of dir() and help()
============================

    To begin with, import any module. 
    To check it's contents use the dir() and for more deatils 
    use help().

.. code :: python

    >>> import decimal

     >>> dir(decimal)
    ['BasicContext', 'Clamped', 'Context', 'ConversionSyntax', 'Decimal', 'DecimalException', 'DecimalTuple', 'DefaultContext',
    'DivisionByZero', 'DivisionImpossible', 'DivisionUndefined', 'ExtendedContext', 'Inexact', 'InvalidContext', 'InvalidOperation',
    'Overflow', 'ROUND_05UP', 'ROUND_CEILING', 'ROUND_DOWN', 'ROUND_FLOOR', 'ROUND_HALF_DOWN', 'ROUND_HALF_EVEN', 
    'ROUND_HALF_UP', 'ROUND_UP', 'Rounded', 'Subnormal', 'Underflow', '_ContextManager', '_Infinity', '_Log10Memoize', 
    '_NaN', '_NegativeInfinity', '_NegativeOne', '_One', '_SignedInfinity', '_WorkRep', '_Zero', '__all__', '__builtins__', '__doc__', 
    '__file__', '__name__', '__package__', '__version__', '_all_zeros', '_condition_map', '_convert_other', '_copy', '_dec_from_triple', 
    '_decimal_lshift_exact', '_dexp', '_div_nearest', '_dlog', '_dlog10', '_dpower', '_exact_half', '_format_align', '_format_number', 
    '_format_sign', '_group_lengths', '_iexp', '_ilog', '_insert_thousands_sep', '_locale', '_log10_digits', '_log10_lb', '_math', 
    '_namedtuple', '_nbits', '_normalize', '_numbers', '_parse_format_specifier', '_parse_format_specifier_regex', '_parser', 
    '_rshift_nearest', '_signals', '_sqrt_nearest', 'getcontext', 'localcontext', 'setcontext']




.. code :: python

        Help on module decimal:

    NAME
       decimal

    FILE
        /usr/lib/python2.7/decimal.py

     MODULE DOCS
        http://docs.python.org/library/decimal

    DESCRIPTION
        This is a Py2.3 implementation of decimal floating point arithmetic based on
        the General Decimal Arithmetic Specification:
    
            http://speleotrove.com/decimal/decarith.html
    
        and IEEE standard 854-1987:
    
            http://en.wikipedia.org/wiki/IEEE_854-1987
    
        Decimal floating point has finite precision with arbitrarily large bounds.
    
        The purpose of this module is to support arithmetic using familiar
        "schoolhouse" rules and to avoid some of the tricky representation
        issues associated with binary floating point.  The package is especially
        useful for financial applications or for contexts where users have
        expectations that are at odds with binary floating point (for instance,
        in binary floating point, 1.00 % 0.1 gives 0.09999999999999995 instead
        of the expected Decimal('0.00') returned by decimal floating point).
    
        Here are some examples of using the decimal module:
    
        >>> from decimal import *
        >>> setcontext(ExtendedContext)
        >>> Decimal(0)
        Decimal('0')
        >>> Decimal('1')
        Decimal('1')
        >>> Decimal('-.0123')
        Decimal('-0.0123')








