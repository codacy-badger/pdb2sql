=======
PDB2SQL
=======

This module is based on :py:mod:`sqlite3`.

.. autoclass:: pdb2sql.pdb2sqlcore.pdb2sql
.. currentmodule:: pdb2sql.pdb2sqlcore.pdb2sql

Process PDB
~~~~~~~~~~~
.. autosummary::
    :toctree: api/

    read_pdb

.. currentmodule:: pdb2sql.pdb2sql_base.pdb2sql_base
.. autosummary::
    :toctree: api/

    exportpdb
    sql2pdb

.. currentmodule:: pdb2sql.pdb2sqlcore.pdb2sql

Get SQL Data
~~~~~~~~~~~~
.. autosummary::
    :toctree: api/

    get
    get_colnames
    get_chains
    get_residues
    get_xyz

Set SQL data
~~~~~~~~~~~~
.. autosummary::
    :toctree: api/

    update
    add_column
    update_column
    update_xyz

Print SQL data
~~~~~~~~~~~~~~
.. autosummary::
    :toctree: api/

    print
    print_colnames

..
    .. automodule:: pdb2sql.pdb2sqlcore
    :members:
    :undoc-members:
    :show-inheritance:
