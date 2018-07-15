****************************
Eclipse IDE 的创建和烧录指南
****************************
:link_to_translation:`en:[English]`

.. important:: 对不起，CMake-based Build System Preview 还没有中文翻译。

		
		* 从 “Providers” 列表中选择 “CDT GCC Build Output Parser”，将 “Compiler command pattern” 修改为 ``xtensa-esp32-elf-(gcc|g\+\+|c\+\+|cc|cpp|clang)``

* 前往 “C/C++ General” -> “Indexer” 属性页面。

	* 去除 "Allow heuristic resolution of includes" 勾选。启用此选项时，Eclipse 有时无法找到正确的头文件目录。

点击 “C/C++ General" -> "Indexer” 属性页。

    * 选择 “Enable project specific settings” 以启用本页上的其他设置。

.. note::

    取消选中 “Allow heuristic resolution of includes”。因为启用此选项时，有时会导致 Eclipse 无法找到正确的头文件目录。