﻿================================================================================
    MFC (MICROSOFT FOUNDATION CLASS) ライブラリ : CSNW_SetUp プロジェクトの概要
===============================================================================

この CSNW_SetUp アプリケーションは、アプリケーション ウィザードによって作成されました。このアプリケーションは MFC の基本的な使い方を示すだけでなく、アプリケーションを作成するための開始点でもあります。

このファイルには、CSNW_SetUp アプリケーションを構成する各ファイルの内容の概要が含まれています。

CSNW_SetUp.vcxproj
    これは、アプリケーション ウィザードで生成された VC++ プロジェクトのメイン プロジェクト ファイルです。ファイルを生成した Visual C++ のバージョンに関する情報と、アプリケーション ウィザードで選択されたプラットフォーム、構成、およびプロジェクト機能に関する情報が含まれています。

CSNW_SetUp.vcxproj.filters
    これは、アプリケーション ウィザードで生成された VC++ プロジェクトのフィルター ファイルです。このファイルには、プロジェクト内のファイルとフィルターとの間の関連付けに関する情報が含まれています。この関連付けは、特定のノードで同様の拡張子を持つファイルのグループ化を示すために IDE で使用されます (たとえば、".cpp" ファイルは "ソース ファイル" フィルターに関連付けられています)。

CSNW_SetUp.h
    これはアプリケーションのメイン ヘッダー ファイルです。
    その他のプロジェクト固有のヘッダー (Resource.h など) が含まれ、CCSNW_SetUpApp アプリケーション クラスを宣言します。

CSNW_SetUp.cpp
    これはメインのアプリケーション ソース ファイルで、CCSNW_SetUpApp アプリケーション クラスが含まれています。

CSNW_SetUp.rc
    これは、プログラムが使用するすべての Microsoft Windows リソースの一覧です。RES サブディレクトリに格納されるアイコン、ビットマップ、およびカーソルをインクルードしています。このファイルは、Microsoft Visual C++ で直接編集できます。プロジェクト リソースは 1041 にあります。

res\CSNW_SetUp.ico
    これはアプリケーションのアイコンとして使用されるアイコン ファイルです。このアイコンは、メイン リソース ファイル CSNW_SetUp.rc にインクルードされます。

res\CSNW_SetUp.rc2
    このファイルには、Microsoft Visual C++ で編集しないリソースが含まれています。リソース エディターで編集できないすべてのリソースは、このファイルに含める必要があります。


/////////////////////////////////////////////////////////////////////////////

アプリケーション ウィザードは 1 つのダイアログ クラスを作成します。

CSNW_SetUpDlg.h, CSNW_SetUpDlg.cpp - ダイアログ
    これらのファイルには、CCSNW_SetUpDlg クラスが含まれます。このクラスはアプリケーションのメイン ダイアログの動作を定義します。ダイアログのテンプレートは、Microsoft Visual C++ で編集できる CSNW_SetUp.rc に含まれています。

/////////////////////////////////////////////////////////////////////////////

その他の機能:

ActiveX コントロール
    ActiveX コントロールを使用するためのサポートがアプリケーションに含まれます。

/////////////////////////////////////////////////////////////////////////////

その他の標準ファイル :

StdAfx.h, StdAfx.cpp
    これらのファイルは、CSNW_SetUp.pch という名前のプリコンパイル済みヘッダー (PCH) ファイルと、StdAfx.obj という名前のプリコンパイル済みの型ファイルをビルドするために使用されます。

Resource.h
    これは、新しいリソース ID を定義する標準のヘッダー ファイルです。このファイルの読み込みおよび更新は、Microsoft Visual C++ で行います。

CSNW_SetUp.manifest
	アプリケーション マニフェスト ファイルは、Windows XP で、特定のバージョンの side-by-side アセンブリに対するアプリケーションの依存関係を説明するために使用されます。ローダーはこの情報を使用して、アセンブリ キャッシュから適切なアセンブリを、またはアプリケーションからプライベート アセンブリを読み込みます。アプリケーション マニフェストは、再頒布用に、アプリケーションの実行可能ファイルと同じフォルダーにインストールされる外部 .manifest ファイルとして含まれているか、またはリソースのフォーム内の実行可能ファイルに含まれています。
/////////////////////////////////////////////////////////////////////////////

その他のメモ :

アプリケーション ウィザードでは "TODO:" を使用して、ユーザーが追加またはカスタマイズする必要のあるソース コードを示します。

アプリケーションが共有 DLL 内で MFC を使用する場合は、MFC DLL を再頒布する必要があります。アプリケーションがオペレーティング システムのロケール以外の言語を使用している場合、対応するローカライズされたリソース mfc110XXX.DLL も再頒布する必要があります
これらのトピックの詳細については、MSDN ドキュメントの Visual C++ アプリケーションの再頒布に関するセクションを参照してください。

/////////////////////////////////////////////////////////////////////////////
