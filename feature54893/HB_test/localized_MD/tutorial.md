---
title: コード エディターでの編集の概要
ms.date: 11/30/2017
ms.technology: vs-ide-general
ms.custom: get-started
ms.topic: tutorial
author: gewarren
ms.author: gewarren
manager: jillfra
dev_langs:
- CSharp
ms.workload:
- multiple
ms.openlocfilehash: 913a5a08dc467ea23d22c2a08a23abfe70b9a736
ms.sourcegitcommit: 94b3a052fb1229c7e7f8804b09c1d403385c7630
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62943954"
---
# <a name="learn-to-use-the-code-editor"></a><span data-ttu-id="fba66-102">コード エディターを使用方法について学習する</span><span class="sxs-lookup"><span data-stu-id="fba66-102">Learn to use the code editor</span></span>

<span data-ttu-id="fba66-103">この 10 分間の Visual Studio のコード エディターの紹介では、ファイルにコードを追加した上で、Visual Studio でコードを記述、コード内を移動、およびコードを理解する簡単な方法をいくつか説明します。</span><span class="sxs-lookup"><span data-stu-id="fba66-103">In this 10-minute introduction to the code editor in Visual Studio, we'll add code to a file to look at some of the ways that Visual Studio makes writing, navigating, and understanding code easier.</span></span>

::: moniker range="vs-2017"

> [!TIP]
> <span data-ttu-id="fba66-104">Visual Studio をまだインストールしていない場合は、[Visual Studio のダウンロード](https://visualstudio.microsoft.com/vs/older-downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=vs+2017+download) ページに移動し、無料試用版をインストールしてください。</span><span class="sxs-lookup"><span data-stu-id="fba66-104">If you haven't already installed Visual Studio, go to the [Visual Studio downloads](https://visualstudio.microsoft.com/vs/older-downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=vs+2017+download) page to install it for free.</span></span>

::: moniker-end

::: moniker range="vs-2019"

> [!TIP]
> <span data-ttu-id="fba66-105">Visual Studio をまだインストールしていない場合は、[Visual Studio のダウンロード](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=inline+link&utm_content=download+vs2019) ページに移動し、無料試用版をインストールしてください。</span><span class="sxs-lookup"><span data-stu-id="fba66-105">If you haven't already installed Visual Studio, go to the [Visual Studio downloads](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=inline+link&utm_content=download+vs2019) page to install it for free.</span></span>

::: moniker-end

<span data-ttu-id="fba66-106">この記事では、既にプログラミング言語を使い慣れていることを前提としています。</span><span class="sxs-lookup"><span data-stu-id="fba66-106">This article assumes you're already familiar with a programming language.</span></span> <span data-ttu-id="fba66-107">使い慣れていない場合は、[Python](../ide/quickstart-python.md) または [C#](../get-started/csharp/tutorial-aspnet-core.md) による Web アプリの作成や、[Visual Basic](../ide/quickstart-visual-basic-console.md) または [C++](../ide/getting-started-with-cpp-in-visual-studio.md) によるコンソール アプリの作成など、プログラミング言語に関するいずれかのクイック スタートを最初に確認することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="fba66-107">If you aren't, we suggest you look at one of the programming quickstarts first, such as create a web app with [Python](../ide/quickstart-python.md) or [C#](../get-started/csharp/tutorial-aspnet-core.md), or create a console app with [Visual Basic](../ide/quickstart-visual-basic-console.md) or [C++](../ide/getting-started-with-cpp-in-visual-studio.md).</span></span>

## <a name="create-a-new-code-file"></a><span data-ttu-id="fba66-108">新しいコード ファイルを作成する</span><span class="sxs-lookup"><span data-stu-id="fba66-108">Create a new code file</span></span>

<span data-ttu-id="fba66-109">新しいファイルを作成し、何らかのコードをそのファイルに追加することから始めます。</span><span class="sxs-lookup"><span data-stu-id="fba66-109">Start by creating a new file and adding some code to it.</span></span>

::: moniker range="vs-2017"

1. <span data-ttu-id="fba66-110">Visual Studio を開きます。</span><span class="sxs-lookup"><span data-stu-id="fba66-110">Open Visual Studio.</span></span>

::: moniker-end

::: moniker range=">=vs-2019"

1. <span data-ttu-id="fba66-111">Visual Studio を開きます。</span><span class="sxs-lookup"><span data-stu-id="fba66-111">Open Visual Studio.</span></span> <span data-ttu-id="fba66-112">スタート ウィンドウで **Esc** キーを押すか、または **[コードなしで続行]** をクリックして、開発環境を開きます。</span><span class="sxs-lookup"><span data-stu-id="fba66-112">Press **Esc** or click **Continue without code** on the start window to open the development environment.</span></span>

::: moniker-end

2. <span data-ttu-id="fba66-113">メニュー バーの **[ファイル]** メニューから、**[新規作成]** > **[ファイル]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-113">From the **File** menu on the menu bar, choose **New** > **File**.</span></span>

3. <span data-ttu-id="fba66-114">**[新しいファイル]** ダイアログ ボックスの **[全般]** カテゴリで、**[Visual C# クラス]** を選択し、**[開く]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-114">In the **New File** dialog box, under the **General** category, choose **Visual C# Class**, and then choose **Open**.</span></span>

   <span data-ttu-id="fba66-115">エディターで新しいファイルが開かれ、C# クラスのスケルトンが表示されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-115">A new file opens in the editor with the skeleton of a C# class.</span></span> <span data-ttu-id="fba66-116">(コード エディターによって提供される利点の一部を活用するために、完全な Visual Studio プロジェクトを作成する必要はありません。必要なのはコード ファイルだけです)</span><span class="sxs-lookup"><span data-stu-id="fba66-116">(Notice that we don't have to create a full Visual Studio project to gain some of the benefits that the code editor offers; all you need is a code file!)</span></span>

   ![Visual Studio での C# コード ファイル](media/tutorial-editor.png)

## <a name="use-code-snippets"></a><span data-ttu-id="fba66-118">コード スニペットを使用する</span><span class="sxs-lookup"><span data-stu-id="fba66-118">Use code snippets</span></span>

<span data-ttu-id="fba66-119">Visual Studio で提供されている便利な*コード スニペット*を使用すると、一般的に使用されるコード ブロックを迅速かつ簡単に生成することができます。</span><span class="sxs-lookup"><span data-stu-id="fba66-119">Visual Studio provides useful *code snippets* that you can use to quickly and easily generate commonly used code blocks.</span></span> <span data-ttu-id="fba66-120">[コード スニペット](../ide/code-snippets.md)は、C#、Visual Basic、C++ など、さまざまなプログラミング言語で使用することができます。</span><span class="sxs-lookup"><span data-stu-id="fba66-120">[Code snippets](../ide/code-snippets.md) are available for different programming languages including C#, Visual Basic, and C++.</span></span> <span data-ttu-id="fba66-121">C# `void Main` スニペットをファイルに追加してみましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-121">Let's add the C# `void Main` snippet to our file.</span></span>

1. <span data-ttu-id="fba66-122">ファイル内の最後の閉じかっこ **}** のすぐ上にカーソルを置き、`svm` という文字を入力します </span><span class="sxs-lookup"><span data-stu-id="fba66-122">Place your cursor just above the final closing brace **}** in the file, and type the characters `svm`.</span></span> <span data-ttu-id="fba66-123">(`svm` は `static void Main` の略です。[Main()](/dotnet/csharp/programming-guide/main-and-command-args/) メソッドは、C# アプリケーションのエントリ ポイントです)。</span><span class="sxs-lookup"><span data-stu-id="fba66-123">(`svm` stands for `static void Main`; the [Main()](/dotnet/csharp/programming-guide/main-and-command-args/) method is the entry point for C# applications.)</span></span>

   <span data-ttu-id="fba66-124">ポップアップ ダイアログ ボックスが `svm` コード スニペットに関する情報を伴って表示されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-124">A pop-up dialog box appears with information about the `svm` code snippet.</span></span>

   ![Visual Studio でのコード スニペット用の IntelliSense](media/tutorial-intellisense-snippet.png)

1. <span data-ttu-id="fba66-126">**Tab** キーを 2 回押すと、コード スニペットが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-126">Press **Tab** twice to insert the code snippet.</span></span>

   <span data-ttu-id="fba66-127">`static void Main()` メソッドの署名がファイルに追加されているのがわかります。</span><span class="sxs-lookup"><span data-stu-id="fba66-127">You see the `static void Main()` method signature get added to the file.</span></span>

<span data-ttu-id="fba66-128">利用できるコード スニペットは、プログラミング言語によって異なります。</span><span class="sxs-lookup"><span data-stu-id="fba66-128">The available code snippets vary for different programming languages.</span></span> <span data-ttu-id="fba66-129">目的の言語で使用可能なコード スニペットを確認するには、**[編集]** > **[IntelliSense]** > **[スニペットの挿入]** の順に選択し、言語のフォルダーを選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-129">You can look at the available code snippets for your language by choosing **Edit** > **IntelliSense** > **Insert Snippet**, and then choosing your language's folder.</span></span> <span data-ttu-id="fba66-130">C# の場合、リストは次のようになります。</span><span class="sxs-lookup"><span data-stu-id="fba66-130">For C#, the list looks like this:</span></span>

![C# コード スニペットのリスト](media/tutorial-code-snippet-list.png)

<span data-ttu-id="fba66-132">このリストには、[クラス](/dotnet/csharp/programming-guide/classes-and-structs/classes)、[コンストラクター](/dotnet/csharp/programming-guide/classes-and-structs/constructors)、[for](/dotnet/csharp/language-reference/keywords/for) ループ、[if](/dotnet/csharp/language-reference/keywords/if-else) ステートメント、[switch](/dotnet/csharp/language-reference/keywords/switch) ステートメントなどを作成するためのスニペットが含まれています。</span><span class="sxs-lookup"><span data-stu-id="fba66-132">The list includes snippets for creating a [class](/dotnet/csharp/programming-guide/classes-and-structs/classes), a [constructor](/dotnet/csharp/programming-guide/classes-and-structs/constructors), a [for](/dotnet/csharp/language-reference/keywords/for) loop, an [if](/dotnet/csharp/language-reference/keywords/if-else) or [switch](/dotnet/csharp/language-reference/keywords/switch) statement, and more.</span></span>

## <a name="comment-out-code"></a><span data-ttu-id="fba66-133">コメント アウト コード</span><span class="sxs-lookup"><span data-stu-id="fba66-133">Comment out code</span></span>

<span data-ttu-id="fba66-134">ツールバー (Visual Studio のメニュー バーの下にあるボタンの列) は、コード作成時の生産性を高めるのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="fba66-134">The toolbar, which is the row of buttons under the menu bar in Visual Studio, can help make you more productive as you code.</span></span> <span data-ttu-id="fba66-135">たとえば、IntelliSense 補完モードの切り替え (特に、[IntelliSense](../ide/using-intellisense.md) は、一致するメソッドの一覧を表示するコーディング支援機能)、行のインデントの増減、またはコンパイルしたくないコードをコメント アウトを行うことができます。</span><span class="sxs-lookup"><span data-stu-id="fba66-135">For example, you can toggle IntelliSense completion mode ([IntelliSense](../ide/using-intellisense.md) is a coding aid that displays a list of matching methods, amongst other things), increase or decrease a line indent, or comment out code that you don't want to compile.</span></span> <span data-ttu-id="fba66-136">このセクションでは、一部のコードをコメント アウトします。</span><span class="sxs-lookup"><span data-stu-id="fba66-136">In this section, we'll comment out some code.</span></span>

![エディターのツール バー](media/tutorial-editor-toolbar.png)

1. <span data-ttu-id="fba66-138">`Main()` メソッド本体に次のコードを貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="fba66-138">Paste the following code into the `Main()` method body.</span></span>

    ```csharp
    // _words is a string array that we'll sort alphabetically
    string[] _words = {
        "the",
        "quick",
        "brown",
        "fox",
        "jumps"
    };

    string[] morewords = {
        "over",
        "the",
        "lazy",
        "dog"
    };

    IEnumerable<string> query = from word in _words
                                orderby word.Length
                                select word;
    ```

1. <span data-ttu-id="fba66-139">`morewords` 変数は現在使用していませんが、後で使用するかもしれないので、完全に削除したくありません。</span><span class="sxs-lookup"><span data-stu-id="fba66-139">We're not using the `morewords` variable, but we may use it later so we don't want to completely delete it.</span></span> <span data-ttu-id="fba66-140">そこで、これらの行をコメント アウトしましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-140">Instead, let's comment out those lines.</span></span> <span data-ttu-id="fba66-141">終了セミコロンまでの `morewords` の定義全体を選択し、ツールバーの **[選択された行をコメント アウトします。]** ボタンを選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-141">Select the entire definition of `morewords` to the closing semi-colon, and then choose the **Comment out the selected lines** button on the toolbar.</span></span> <span data-ttu-id="fba66-142">キーボードを使用する場合は、**Ctrl** + **K** キー、**Ctrl** + **C** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-142">If you prefer to use the keyboard, press **Ctrl**+**K**, **Ctrl**+**C**.</span></span>

   ![コメント アウト ボタン](media/tutorial-comment-out.png)

   <span data-ttu-id="fba66-144">選択した各列の先頭に C# コメント文字 `//` を追加すると、コードがコメント アウトされます。</span><span class="sxs-lookup"><span data-stu-id="fba66-144">The C# comment characters `//` are added to the beginning of each selected line to comment out the code.</span></span>

## <a name="collapse-code-blocks"></a><span data-ttu-id="fba66-145">コード ブロックを折りたたむ</span><span class="sxs-lookup"><span data-stu-id="fba66-145">Collapse code blocks</span></span>

<span data-ttu-id="fba66-146">生成された [constructor](/dotnet/csharp/programming-guide/classes-and-structs/constructors) for `Class1` の空のコンストラクターは表示したくありません。コードのビューを整理するために、ビューを折りたたみましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-146">We don't want to see the empty [constructor](/dotnet/csharp/programming-guide/classes-and-structs/constructors) for `Class1` that was generated, so to unclutter our view of the code, let's collapse it.</span></span> <span data-ttu-id="fba66-147">コンストラクターの最初の行の余白にある、内部にマイナス記号が表示された小さな灰色のボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-147">Choose the small gray box with the minus sign inside it in the margin of the first line of the constructor.</span></span> <span data-ttu-id="fba66-148">または、キーボードを使用している場合は、コンストラクター コード内の任意の場所にカーソルを置き、**Ctrl** + **M** キー、**Ctrl** + **M** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-148">Or, if you're a keyboard user, place the cursor anywhere in the constructor code and press **Ctrl**+**M**, **Ctrl**+**M**.</span></span>

![アウトライン折りたたみボタン](media/tutorial-collapse.png)

<span data-ttu-id="fba66-150">コード ブロックが最初の行に折りたたまれ、後続に省略記号 (`...`) が表示されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-150">The code block collapses to just the first line, followed by an ellipsis (`...`).</span></span> <span data-ttu-id="fba66-151">コード ブロックを再度展開するには、現在内部にプラス記号が表示されている同じ灰色のボックスをクリックするか、**Ctrl**+**M** キー、**Ctrl**+**M** キーをもう一度押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-151">To expand the code block again, click the same gray box that now has a plus sign in it, or press **Ctrl**+**M**, **Ctrl**+**M** again.</span></span> <span data-ttu-id="fba66-152">これは、[アウトライン](../ide/outlining.md)機能と呼ばれ、長いメソッドまたはクラス全体を折りたたむ場合に特に便利です。</span><span class="sxs-lookup"><span data-stu-id="fba66-152">This feature is called [Outlining](../ide/outlining.md) and is especially useful when you're collapsing long methods or entire classes.</span></span>

## <a name="view-symbol-definitions"></a><span data-ttu-id="fba66-153">シンボル定義の表示</span><span class="sxs-lookup"><span data-stu-id="fba66-153">View symbol definitions</span></span>

<span data-ttu-id="fba66-154">Visual Studio エディターでは、型やメソッドなどの定義の検査を容易に行うことができます。1 つの方法として、たとえば、シンボルが参照されている任意の場所で **[定義へ移動]** を選択して、定義を含むファイルに移動します。</span><span class="sxs-lookup"><span data-stu-id="fba66-154">The Visual Studio editor makes it easy to inspect the definition of a type, method, etc. One way is to navigate to the file that contains the definition, for example by choosing **Go to Definition** anywhere the symbol is referenced.</span></span> <span data-ttu-id="fba66-155">作業中のファイルからフォーカスを移動しないより迅速な方法としては、[[定義をここに表示]](../ide/go-to-and-peek-definition.md#peek-definition) を使用します。</span><span class="sxs-lookup"><span data-stu-id="fba66-155">An even quicker way that doesn't move your focus away from the file you're working in is to use [Peek Definition](../ide/go-to-and-peek-definition.md#peek-definition).</span></span> <span data-ttu-id="fba66-156">`string` 型の定義を参照してみましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-156">Let's peek at the definition of the `string` type.</span></span>

1. <span data-ttu-id="fba66-157">`string` が出現している箇所を右クリックし、コンテンツ メニューから **[定義をここに表示]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-157">Right-click on any occurrence of `string` and choose **Peek Definition** from the content menu.</span></span> <span data-ttu-id="fba66-158">または、**Alt** + **F12** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-158">Or, press **Alt**+**F12**.</span></span>

   <span data-ttu-id="fba66-159">`String` クラスの定義を含むポップアップ ウィンドウが表示されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-159">A pop-up window appears with the definition of the `String` class.</span></span> <span data-ttu-id="fba66-160">ポップアップ ウィンドウ内をスクロールすることも、参照しているコードから別の種類の定義を参照することもできます。</span><span class="sxs-lookup"><span data-stu-id="fba66-160">You can scroll within the pop-up window, or even peek at the definition of another type from the peeked code.</span></span>

   ![コード定義ウィンドウ](media/tutorial-peek-definition.png)

1. <span data-ttu-id="fba66-162">表示された定義ウィンドウを閉じるには、ポップアップ ウィンドウの右上にある、内部に "x" が表示された小さなボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-162">Close the peeked definition window by choosing the small box with an "x" at the top right of the pop-up window.</span></span>

## <a name="use-intellisense-to-complete-words"></a><span data-ttu-id="fba66-163">IntelliSense を使用した入力補完</span><span class="sxs-lookup"><span data-stu-id="fba66-163">Use IntelliSense to complete words</span></span>

<span data-ttu-id="fba66-164">コードを記述する場合、[IntelliSense](../ide/using-intellisense.md) は貴重なリソースです。</span><span class="sxs-lookup"><span data-stu-id="fba66-164">[IntelliSense](../ide/using-intellisense.md) is an invaluable resource when you're coding.</span></span> <span data-ttu-id="fba66-165">このリソースでは、使用可能な型のメンバーに関する情報、またはメソッドの各種オーバーロードのためのパラメーターの詳細を表示できます。</span><span class="sxs-lookup"><span data-stu-id="fba66-165">It can show you information about available members of a type, or parameter details for different overloads of a method.</span></span> <span data-ttu-id="fba66-166">また、IntelliSense を使用すると、単語を区別するために十分な文字を入力した後に入力補完を利用することができます。</span><span class="sxs-lookup"><span data-stu-id="fba66-166">You can also use IntelliSense to complete a word after you type enough characters to disambiguate it.</span></span> <span data-ttu-id="fba66-167">プログラムからの出力が表示される標準的な場所であるコンソール ウィンドウに、順序付けされた文字列を出力するコード行を追加してみましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-167">Let's add a line of code to print out the ordered strings to the console window, which is the standard place for output from the program to go.</span></span>

1. <span data-ttu-id="fba66-168">`query` 変数の下で、次のコードの入力を開始します。</span><span class="sxs-lookup"><span data-stu-id="fba66-168">Below the `query` variable, start typing the following code:</span></span>

   ```csharp
   foreach (string str in qu
   ```

   <span data-ttu-id="fba66-169">IntelliSense が `query` シンボルに関する**クイック ヒント**を表示しているのがわかります。</span><span class="sxs-lookup"><span data-stu-id="fba66-169">You see IntelliSense show you **Quick Info** about the `query` symbol.</span></span>

   ![Visual Studio での IntelliSense の入力候補](media/tutorial-intellisense-completion-list.png)

1. <span data-ttu-id="fba66-171">IntelliSense の "入力候補" 機能を使用して単語 `query` の残りを挿入するには、**Tab** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-171">To insert the rest of the word `query` by using IntelliSense's word completion functionality, press **Tab**.</span></span>

1. <span data-ttu-id="fba66-172">次のコードのように、コード ブロックを完成させます。</span><span class="sxs-lookup"><span data-stu-id="fba66-172">Finish off the code block to look like the following code.</span></span> <span data-ttu-id="fba66-173">コード スニペットを使用して再度実行することもできます。それには、`cw` を入力してから、**Tab** キーを 2 回押して、`Console.WriteLine` コードを生成します。</span><span class="sxs-lookup"><span data-stu-id="fba66-173">You can even practice using code snippets again by entering `cw` and then pressing **Tab** twice to generate the `Console.WriteLine` code.</span></span>

   ```csharp
   foreach (string str in query)
   {
      Console.WriteLine(str);
   }
   ```

## <a name="refactor-a-name"></a><span data-ttu-id="fba66-174">名前のリファクタリング</span><span class="sxs-lookup"><span data-stu-id="fba66-174">Refactor a name</span></span>

<span data-ttu-id="fba66-175">だれも最初から適切なコードは記述できないものです。変更を必要とする可能性のある要素の 1 つに、変数またはメソッドの名前があります。</span><span class="sxs-lookup"><span data-stu-id="fba66-175">Nobody gets code right the first time, and one of the things you might have to change is the name of a variable or method.</span></span> <span data-ttu-id="fba66-176">Visual Studio の[リファクタリング](../ide/refactoring-in-visual-studio.md)機能を使用して、`_words` 変数の名前を `words` に変更してみましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-176">Let's try out Visual Studio's [refactor](../ide/refactoring-in-visual-studio.md) functionality to rename the `_words` variable to `words`.</span></span>

1. <span data-ttu-id="fba66-177">`_words` 変数の定義にカーソルを置き、右クリックまたはコンテキスト メニューから **[名前の変更]** を選択するか、**Ctrl**+**R** キー、**Ctrl**+**R** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-177">Place your cursor over the definition of the `_words` variable, and choose **Rename** from the right-click or context menu, or press **Ctrl**+**R**, **Ctrl**+**R**.</span></span>

   <span data-ttu-id="fba66-178">エディターの右上に **[名前の変更]** ダイアログ ボックスがポップアップ表示されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-178">A pop-up **Rename** dialog box appears at the top right of the editor.</span></span>

1. <span data-ttu-id="fba66-179">目的の名前 **words** を入力します。</span><span class="sxs-lookup"><span data-stu-id="fba66-179">Enter the desired name **words**.</span></span> <span data-ttu-id="fba66-180">クエリ内の `words` への参照も名前が自動的に変更されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="fba66-180">Notice that the reference to `words` in the query is also automatically renamed.</span></span> <span data-ttu-id="fba66-181">**Enter** キーを押す前に、**[名前の変更]** ポップアップ ボックスで **[コメントを含める]** チェック ボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-181">Before you press **Enter**, select the **Include comments** checkbox in the **Rename** pop-up box.</span></span>

   ![[名前の変更] ダイアログ ボックス](media/tutorial-rename.png)

1. <span data-ttu-id="fba66-183">**Enter** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-183">Press **Enter**.</span></span>

   <span data-ttu-id="fba66-184">`words` の出現箇所とコード コメント内の `words` への参照箇所の両方で名前が変更されました。</span><span class="sxs-lookup"><span data-stu-id="fba66-184">Both occurrences of `words` have been renamed, as well as the reference to `words` in the code comment.</span></span>

## <a name="next-steps"></a><span data-ttu-id="fba66-185">次の手順</span><span class="sxs-lookup"><span data-stu-id="fba66-185">Next steps</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="fba66-186">プロジェクトとソリューションについて学習する</span><span class="sxs-lookup"><span data-stu-id="fba66-186">Learn about projects and solutions</span></span>](../get-started/tutorial-projects-solutions.md)

## <a name="see-also"></a><span data-ttu-id="fba66-187">関連項目</span><span class="sxs-lookup"><span data-stu-id="fba66-187">See also</span></span>

- [<span data-ttu-id="fba66-188">コード スニペット</span><span class="sxs-lookup"><span data-stu-id="fba66-188">Code snippets</span></span>](../ide/code-snippets.md)
- [<span data-ttu-id="fba66-189">コード間の移動</span><span class="sxs-lookup"><span data-stu-id="fba66-189">Navigate code</span></span>](../ide/navigating-code.md)
- [<span data-ttu-id="fba66-190">アウトライン</span><span class="sxs-lookup"><span data-stu-id="fba66-190">Outlining</span></span>](../ide/outlining.md)
- <span data-ttu-id="fba66-191">[[定義へ移動] と [定義をここに表示]](../ide/go-to-and-peek-definition.md)</span><span class="sxs-lookup"><span data-stu-id="fba66-191">[Go To Definition and Peek Definition](../ide/go-to-and-peek-definition.md)</span></span>
- [<span data-ttu-id="fba66-192">リファクタリング</span><span class="sxs-lookup"><span data-stu-id="fba66-192">Refactoring</span></span>](../ide/refactoring-in-visual-studio.md)
- [<span data-ttu-id="fba66-193">IntelliSense を使用する</span><span class="sxs-lookup"><span data-stu-id="fba66-193">Use IntelliSense</span></span>](../ide/using-intellisense.md)---
title: コード エディターでの編集の概要
ms.date: 11/30/2017
ms.technology: vs-ide-general
ms.custom: get-started
ms.topic: tutorial
author: gewarren
ms.author: gewarren
manager: jillfra
dev_langs:
- CSharp
ms.workload:
- multiple
ms.openlocfilehash: 913a5a08dc467ea23d22c2a08a23abfe70b9a736
ms.sourcegitcommit: 94b3a052fb1229c7e7f8804b09c1d403385c7630
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "62943954"
---
# <a name="learn-to-use-the-code-editor"></a><span data-ttu-id="fba66-102">コード エディターを使用方法について学習する</span><span class="sxs-lookup"><span data-stu-id="fba66-102">Learn to use the code editor</span></span>

<span data-ttu-id="fba66-103">この 10 分間の Visual Studio のコード エディターの紹介では、ファイルにコードを追加した上で、Visual Studio でコードを記述、コード内を移動、およびコードを理解する簡単な方法をいくつか説明します。</span><span class="sxs-lookup"><span data-stu-id="fba66-103">In this 10-minute introduction to the code editor in Visual Studio, we'll add code to a file to look at some of the ways that Visual Studio makes writing, navigating, and understanding code easier.</span></span>

::: moniker range="vs-2017"

> [!TIP]
> <span data-ttu-id="fba66-104">Visual Studio をまだインストールしていない場合は、[Visual Studio のダウンロード](https://visualstudio.microsoft.com/vs/older-downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=vs+2017+download) ページに移動し、無料試用版をインストールしてください。</span><span class="sxs-lookup"><span data-stu-id="fba66-104">If you haven't already installed Visual Studio, go to the [Visual Studio downloads](https://visualstudio.microsoft.com/vs/older-downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=vs+2017+download) page to install it for free.</span></span>

::: moniker-end

::: moniker range="vs-2019"

> [!TIP]
> <span data-ttu-id="fba66-105">Visual Studio をまだインストールしていない場合は、[Visual Studio のダウンロード](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=inline+link&utm_content=download+vs2019) ページに移動し、無料試用版をインストールしてください。</span><span class="sxs-lookup"><span data-stu-id="fba66-105">If you haven't already installed Visual Studio, go to the [Visual Studio downloads](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=inline+link&utm_content=download+vs2019) page to install it for free.</span></span>

::: moniker-end

<span data-ttu-id="fba66-106">この記事では、既にプログラミング言語を使い慣れていることを前提としています。</span><span class="sxs-lookup"><span data-stu-id="fba66-106">This article assumes you're already familiar with a programming language.</span></span> <span data-ttu-id="fba66-107">使い慣れていない場合は、[Python](../ide/quickstart-python.md) または [C#](../get-started/csharp/tutorial-aspnet-core.md) による Web アプリの作成や、[Visual Basic](../ide/quickstart-visual-basic-console.md) または [C++](../ide/getting-started-with-cpp-in-visual-studio.md) によるコンソール アプリの作成など、プログラミング言語に関するいずれかのクイック スタートを最初に確認することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="fba66-107">If you aren't, we suggest you look at one of the programming quickstarts first, such as create a web app with [Python](../ide/quickstart-python.md) or [C#](../get-started/csharp/tutorial-aspnet-core.md), or create a console app with [Visual Basic](../ide/quickstart-visual-basic-console.md) or [C++](../ide/getting-started-with-cpp-in-visual-studio.md).</span></span>

## <a name="create-a-new-code-file"></a><span data-ttu-id="fba66-108">新しいコード ファイルを作成する</span><span class="sxs-lookup"><span data-stu-id="fba66-108">Create a new code file</span></span>

<span data-ttu-id="fba66-109">新しいファイルを作成し、何らかのコードをそのファイルに追加することから始めます。</span><span class="sxs-lookup"><span data-stu-id="fba66-109">Start by creating a new file and adding some code to it.</span></span>

::: moniker range="vs-2017"

1. <span data-ttu-id="fba66-110">Visual Studio を開きます。</span><span class="sxs-lookup"><span data-stu-id="fba66-110">Open Visual Studio.</span></span>

::: moniker-end

::: moniker range=">=vs-2019"

1. <span data-ttu-id="fba66-111">Visual Studio を開きます。</span><span class="sxs-lookup"><span data-stu-id="fba66-111">Open Visual Studio.</span></span> <span data-ttu-id="fba66-112">スタート ウィンドウで **Esc** キーを押すか、または **[コードなしで続行]** をクリックして、開発環境を開きます。</span><span class="sxs-lookup"><span data-stu-id="fba66-112">Press **Esc** or click **Continue without code** on the start window to open the development environment.</span></span>

::: moniker-end

2. <span data-ttu-id="fba66-113">メニュー バーの **[ファイル]** メニューから、**[新規作成]** > **[ファイル]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-113">From the **File** menu on the menu bar, choose **New** > **File**.</span></span>

3. <span data-ttu-id="fba66-114">**[新しいファイル]** ダイアログ ボックスの **[全般]** カテゴリで、**[Visual C# クラス]** を選択し、**[開く]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-114">In the **New File** dialog box, under the **General** category, choose **Visual C# Class**, and then choose **Open**.</span></span>

   <span data-ttu-id="fba66-115">エディターで新しいファイルが開かれ、C# クラスのスケルトンが表示されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-115">A new file opens in the editor with the skeleton of a C# class.</span></span> <span data-ttu-id="fba66-116">(コード エディターによって提供される利点の一部を活用するために、完全な Visual Studio プロジェクトを作成する必要はありません。必要なのはコード ファイルだけです)</span><span class="sxs-lookup"><span data-stu-id="fba66-116">(Notice that we don't have to create a full Visual Studio project to gain some of the benefits that the code editor offers; all you need is a code file!)</span></span>

   ![Visual Studio での C# コード ファイル](media/tutorial-editor.png)

## <a name="use-code-snippets"></a><span data-ttu-id="fba66-118">コード スニペットを使用する</span><span class="sxs-lookup"><span data-stu-id="fba66-118">Use code snippets</span></span>

<span data-ttu-id="fba66-119">Visual Studio で提供されている便利な*コード スニペット*を使用すると、一般的に使用されるコード ブロックを迅速かつ簡単に生成することができます。</span><span class="sxs-lookup"><span data-stu-id="fba66-119">Visual Studio provides useful *code snippets* that you can use to quickly and easily generate commonly used code blocks.</span></span> <span data-ttu-id="fba66-120">[コード スニペット](../ide/code-snippets.md)は、C#、Visual Basic、C++ など、さまざまなプログラミング言語で使用することができます。</span><span class="sxs-lookup"><span data-stu-id="fba66-120">[Code snippets](../ide/code-snippets.md) are available for different programming languages including C#, Visual Basic, and C++.</span></span> <span data-ttu-id="fba66-121">C# `void Main` スニペットをファイルに追加してみましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-121">Let's add the C# `void Main` snippet to our file.</span></span>

1. <span data-ttu-id="fba66-122">ファイル内の最後の閉じかっこ **}** のすぐ上にカーソルを置き、`svm` という文字を入力します </span><span class="sxs-lookup"><span data-stu-id="fba66-122">Place your cursor just above the final closing brace **}** in the file, and type the characters `svm`.</span></span> <span data-ttu-id="fba66-123">(`svm` は `static void Main` の略です。[Main()](/dotnet/csharp/programming-guide/main-and-command-args/) メソッドは、C# アプリケーションのエントリ ポイントです)。</span><span class="sxs-lookup"><span data-stu-id="fba66-123">(`svm` stands for `static void Main`; the [Main()](/dotnet/csharp/programming-guide/main-and-command-args/) method is the entry point for C# applications.)</span></span>

   <span data-ttu-id="fba66-124">ポップアップ ダイアログ ボックスが `svm` コード スニペットに関する情報を伴って表示されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-124">A pop-up dialog box appears with information about the `svm` code snippet.</span></span>

   ![Visual Studio でのコード スニペット用の IntelliSense](media/tutorial-intellisense-snippet.png)

1. <span data-ttu-id="fba66-126">**Tab** キーを 2 回押すと、コード スニペットが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-126">Press **Tab** twice to insert the code snippet.</span></span>

   <span data-ttu-id="fba66-127">`static void Main()` メソッドの署名がファイルに追加されているのがわかります。</span><span class="sxs-lookup"><span data-stu-id="fba66-127">You see the `static void Main()` method signature get added to the file.</span></span>

<span data-ttu-id="fba66-128">利用できるコード スニペットは、プログラミング言語によって異なります。</span><span class="sxs-lookup"><span data-stu-id="fba66-128">The available code snippets vary for different programming languages.</span></span> <span data-ttu-id="fba66-129">目的の言語で使用可能なコード スニペットを確認するには、**[編集]** > **[IntelliSense]** > **[スニペットの挿入]** の順に選択し、言語のフォルダーを選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-129">You can look at the available code snippets for your language by choosing **Edit** > **IntelliSense** > **Insert Snippet**, and then choosing your language's folder.</span></span> <span data-ttu-id="fba66-130">C# の場合、リストは次のようになります。</span><span class="sxs-lookup"><span data-stu-id="fba66-130">For C#, the list looks like this:</span></span>

![C# コード スニペットのリスト](media/tutorial-code-snippet-list.png)

<span data-ttu-id="fba66-132">このリストには、[クラス](/dotnet/csharp/programming-guide/classes-and-structs/classes)、[コンストラクター](/dotnet/csharp/programming-guide/classes-and-structs/constructors)、[for](/dotnet/csharp/language-reference/keywords/for) ループ、[if](/dotnet/csharp/language-reference/keywords/if-else) ステートメント、[switch](/dotnet/csharp/language-reference/keywords/switch) ステートメントなどを作成するためのスニペットが含まれています。</span><span class="sxs-lookup"><span data-stu-id="fba66-132">The list includes snippets for creating a [class](/dotnet/csharp/programming-guide/classes-and-structs/classes), a [constructor](/dotnet/csharp/programming-guide/classes-and-structs/constructors), a [for](/dotnet/csharp/language-reference/keywords/for) loop, an [if](/dotnet/csharp/language-reference/keywords/if-else) or [switch](/dotnet/csharp/language-reference/keywords/switch) statement, and more.</span></span>

## <a name="comment-out-code"></a><span data-ttu-id="fba66-133">コメント アウト コード</span><span class="sxs-lookup"><span data-stu-id="fba66-133">Comment out code</span></span>

<span data-ttu-id="fba66-134">ツールバー (Visual Studio のメニュー バーの下にあるボタンの列) は、コード作成時の生産性を高めるのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="fba66-134">The toolbar, which is the row of buttons under the menu bar in Visual Studio, can help make you more productive as you code.</span></span> <span data-ttu-id="fba66-135">たとえば、IntelliSense 補完モードの切り替え (特に、[IntelliSense](../ide/using-intellisense.md) は、一致するメソッドの一覧を表示するコーディング支援機能)、行のインデントの増減、またはコンパイルしたくないコードをコメント アウトを行うことができます。</span><span class="sxs-lookup"><span data-stu-id="fba66-135">For example, you can toggle IntelliSense completion mode ([IntelliSense](../ide/using-intellisense.md) is a coding aid that displays a list of matching methods, amongst other things), increase or decrease a line indent, or comment out code that you don't want to compile.</span></span> <span data-ttu-id="fba66-136">このセクションでは、一部のコードをコメント アウトします。</span><span class="sxs-lookup"><span data-stu-id="fba66-136">In this section, we'll comment out some code.</span></span>

![エディターのツール バー](media/tutorial-editor-toolbar.png)

1. <span data-ttu-id="fba66-138">`Main()` メソッド本体に次のコードを貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="fba66-138">Paste the following code into the `Main()` method body.</span></span>

    ```csharp
    // _words is a string array that we'll sort alphabetically
    string[] _words = {
        "the",
        "quick",
        "brown",
        "fox",
        "jumps"
    };

    string[] morewords = {
        "over",
        "the",
        "lazy",
        "dog"
    };

    IEnumerable<string> query = from word in _words
                                orderby word.Length
                                select word;
    ```

1. <span data-ttu-id="fba66-139">`morewords` 変数は現在使用していませんが、後で使用するかもしれないので、完全に削除したくありません。</span><span class="sxs-lookup"><span data-stu-id="fba66-139">We're not using the `morewords` variable, but we may use it later so we don't want to completely delete it.</span></span> <span data-ttu-id="fba66-140">そこで、これらの行をコメント アウトしましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-140">Instead, let's comment out those lines.</span></span> <span data-ttu-id="fba66-141">終了セミコロンまでの `morewords` の定義全体を選択し、ツールバーの **[選択された行をコメント アウトします。]** ボタンを選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-141">Select the entire definition of `morewords` to the closing semi-colon, and then choose the **Comment out the selected lines** button on the toolbar.</span></span> <span data-ttu-id="fba66-142">キーボードを使用する場合は、**Ctrl** + **K** キー、**Ctrl** + **C** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-142">If you prefer to use the keyboard, press **Ctrl**+**K**, **Ctrl**+**C**.</span></span>

   ![コメント アウト ボタン](media/tutorial-comment-out.png)

   <span data-ttu-id="fba66-144">選択した各列の先頭に C# コメント文字 `//` を追加すると、コードがコメント アウトされます。</span><span class="sxs-lookup"><span data-stu-id="fba66-144">The C# comment characters `//` are added to the beginning of each selected line to comment out the code.</span></span>

## <a name="collapse-code-blocks"></a><span data-ttu-id="fba66-145">コード ブロックを折りたたむ</span><span class="sxs-lookup"><span data-stu-id="fba66-145">Collapse code blocks</span></span>

<span data-ttu-id="fba66-146">生成された [constructor](/dotnet/csharp/programming-guide/classes-and-structs/constructors) for `Class1` の空のコンストラクターは表示したくありません。コードのビューを整理するために、ビューを折りたたみましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-146">We don't want to see the empty [constructor](/dotnet/csharp/programming-guide/classes-and-structs/constructors) for `Class1` that was generated, so to unclutter our view of the code, let's collapse it.</span></span> <span data-ttu-id="fba66-147">コンストラクターの最初の行の余白にある、内部にマイナス記号が表示された小さな灰色のボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-147">Choose the small gray box with the minus sign inside it in the margin of the first line of the constructor.</span></span> <span data-ttu-id="fba66-148">または、キーボードを使用している場合は、コンストラクター コード内の任意の場所にカーソルを置き、**Ctrl** + **M** キー、**Ctrl** + **M** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-148">Or, if you're a keyboard user, place the cursor anywhere in the constructor code and press **Ctrl**+**M**, **Ctrl**+**M**.</span></span>

![アウトライン折りたたみボタン](media/tutorial-collapse.png)

<span data-ttu-id="fba66-150">コード ブロックが最初の行に折りたたまれ、後続に省略記号 (`...`) が表示されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-150">The code block collapses to just the first line, followed by an ellipsis (`...`).</span></span> <span data-ttu-id="fba66-151">コード ブロックを再度展開するには、現在内部にプラス記号が表示されている同じ灰色のボックスをクリックするか、**Ctrl**+**M** キー、**Ctrl**+**M** キーをもう一度押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-151">To expand the code block again, click the same gray box that now has a plus sign in it, or press **Ctrl**+**M**, **Ctrl**+**M** again.</span></span> <span data-ttu-id="fba66-152">これは、[アウトライン](../ide/outlining.md)機能と呼ばれ、長いメソッドまたはクラス全体を折りたたむ場合に特に便利です。</span><span class="sxs-lookup"><span data-stu-id="fba66-152">This feature is called [Outlining](../ide/outlining.md) and is especially useful when you're collapsing long methods or entire classes.</span></span>

## <a name="view-symbol-definitions"></a><span data-ttu-id="fba66-153">シンボル定義の表示</span><span class="sxs-lookup"><span data-stu-id="fba66-153">View symbol definitions</span></span>

<span data-ttu-id="fba66-154">Visual Studio エディターでは、型やメソッドなどの定義の検査を容易に行うことができます。1 つの方法として、たとえば、シンボルが参照されている任意の場所で **[定義へ移動]** を選択して、定義を含むファイルに移動します。</span><span class="sxs-lookup"><span data-stu-id="fba66-154">The Visual Studio editor makes it easy to inspect the definition of a type, method, etc. One way is to navigate to the file that contains the definition, for example by choosing **Go to Definition** anywhere the symbol is referenced.</span></span> <span data-ttu-id="fba66-155">作業中のファイルからフォーカスを移動しないより迅速な方法としては、[[定義をここに表示]](../ide/go-to-and-peek-definition.md#peek-definition) を使用します。</span><span class="sxs-lookup"><span data-stu-id="fba66-155">An even quicker way that doesn't move your focus away from the file you're working in is to use [Peek Definition](../ide/go-to-and-peek-definition.md#peek-definition).</span></span> <span data-ttu-id="fba66-156">`string` 型の定義を参照してみましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-156">Let's peek at the definition of the `string` type.</span></span>

1. <span data-ttu-id="fba66-157">`string` が出現している箇所を右クリックし、コンテンツ メニューから **[定義をここに表示]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-157">Right-click on any occurrence of `string` and choose **Peek Definition** from the content menu.</span></span> <span data-ttu-id="fba66-158">または、**Alt** + **F12** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-158">Or, press **Alt**+**F12**.</span></span>

   <span data-ttu-id="fba66-159">`String` クラスの定義を含むポップアップ ウィンドウが表示されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-159">A pop-up window appears with the definition of the `String` class.</span></span> <span data-ttu-id="fba66-160">ポップアップ ウィンドウ内をスクロールすることも、参照しているコードから別の種類の定義を参照することもできます。</span><span class="sxs-lookup"><span data-stu-id="fba66-160">You can scroll within the pop-up window, or even peek at the definition of another type from the peeked code.</span></span>

   ![コード定義ウィンドウ](media/tutorial-peek-definition.png)

1. <span data-ttu-id="fba66-162">表示された定義ウィンドウを閉じるには、ポップアップ ウィンドウの右上にある、内部に "x" が表示された小さなボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-162">Close the peeked definition window by choosing the small box with an "x" at the top right of the pop-up window.</span></span>

## <a name="use-intellisense-to-complete-words"></a><span data-ttu-id="fba66-163">IntelliSense を使用した入力補完</span><span class="sxs-lookup"><span data-stu-id="fba66-163">Use IntelliSense to complete words</span></span>

<span data-ttu-id="fba66-164">コードを記述する場合、[IntelliSense](../ide/using-intellisense.md) は貴重なリソースです。</span><span class="sxs-lookup"><span data-stu-id="fba66-164">[IntelliSense](../ide/using-intellisense.md) is an invaluable resource when you're coding.</span></span> <span data-ttu-id="fba66-165">このリソースでは、使用可能な型のメンバーに関する情報、またはメソッドの各種オーバーロードのためのパラメーターの詳細を表示できます。</span><span class="sxs-lookup"><span data-stu-id="fba66-165">It can show you information about available members of a type, or parameter details for different overloads of a method.</span></span> <span data-ttu-id="fba66-166">また、IntelliSense を使用すると、単語を区別するために十分な文字を入力した後に入力補完を利用することができます。</span><span class="sxs-lookup"><span data-stu-id="fba66-166">You can also use IntelliSense to complete a word after you type enough characters to disambiguate it.</span></span> <span data-ttu-id="fba66-167">プログラムからの出力が表示される標準的な場所であるコンソール ウィンドウに、順序付けされた文字列を出力するコード行を追加してみましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-167">Let's add a line of code to print out the ordered strings to the console window, which is the standard place for output from the program to go.</span></span>

1. <span data-ttu-id="fba66-168">`query` 変数の下で、次のコードの入力を開始します。</span><span class="sxs-lookup"><span data-stu-id="fba66-168">Below the `query` variable, start typing the following code:</span></span>

   ```csharp
   foreach (string str in qu
   ```

   <span data-ttu-id="fba66-169">IntelliSense が `query` シンボルに関する**クイック ヒント**を表示しているのがわかります。</span><span class="sxs-lookup"><span data-stu-id="fba66-169">You see IntelliSense show you **Quick Info** about the `query` symbol.</span></span>

   ![Visual Studio での IntelliSense の入力候補](media/tutorial-intellisense-completion-list.png)

1. <span data-ttu-id="fba66-171">IntelliSense の "入力候補" 機能を使用して単語 `query` の残りを挿入するには、**Tab** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-171">To insert the rest of the word `query` by using IntelliSense's word completion functionality, press **Tab**.</span></span>

1. <span data-ttu-id="fba66-172">次のコードのように、コード ブロックを完成させます。</span><span class="sxs-lookup"><span data-stu-id="fba66-172">Finish off the code block to look like the following code.</span></span> <span data-ttu-id="fba66-173">コード スニペットを使用して再度実行することもできます。それには、`cw` を入力してから、**Tab** キーを 2 回押して、`Console.WriteLine` コードを生成します。</span><span class="sxs-lookup"><span data-stu-id="fba66-173">You can even practice using code snippets again by entering `cw` and then pressing **Tab** twice to generate the `Console.WriteLine` code.</span></span>

   ```csharp
   foreach (string str in query)
   {
      Console.WriteLine(str);
   }
   ```

## <a name="refactor-a-name"></a><span data-ttu-id="fba66-174">名前のリファクタリング</span><span class="sxs-lookup"><span data-stu-id="fba66-174">Refactor a name</span></span>

<span data-ttu-id="fba66-175">だれも最初から適切なコードは記述できないものです。変更を必要とする可能性のある要素の 1 つに、変数またはメソッドの名前があります。</span><span class="sxs-lookup"><span data-stu-id="fba66-175">Nobody gets code right the first time, and one of the things you might have to change is the name of a variable or method.</span></span> <span data-ttu-id="fba66-176">Visual Studio の[リファクタリング](../ide/refactoring-in-visual-studio.md)機能を使用して、`_words` 変数の名前を `words` に変更してみましょう。</span><span class="sxs-lookup"><span data-stu-id="fba66-176">Let's try out Visual Studio's [refactor](../ide/refactoring-in-visual-studio.md) functionality to rename the `_words` variable to `words`.</span></span>

1. <span data-ttu-id="fba66-177">`_words` 変数の定義にカーソルを置き、右クリックまたはコンテキスト メニューから **[名前の変更]** を選択するか、**Ctrl**+**R** キー、**Ctrl**+**R** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-177">Place your cursor over the definition of the `_words` variable, and choose **Rename** from the right-click or context menu, or press **Ctrl**+**R**, **Ctrl**+**R**.</span></span>

   <span data-ttu-id="fba66-178">エディターの右上に **[名前の変更]** ダイアログ ボックスがポップアップ表示されます。</span><span class="sxs-lookup"><span data-stu-id="fba66-178">A pop-up **Rename** dialog box appears at the top right of the editor.</span></span>

1. <span data-ttu-id="fba66-179">目的の名前 **words** を入力します。</span><span class="sxs-lookup"><span data-stu-id="fba66-179">Enter the desired name **words**.</span></span> <span data-ttu-id="fba66-180">クエリ内の `words` への参照も名前が自動的に変更されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="fba66-180">Notice that the reference to `words` in the query is also automatically renamed.</span></span> <span data-ttu-id="fba66-181">**Enter** キーを押す前に、**[名前の変更]** ポップアップ ボックスで **[コメントを含める]** チェック ボックスを選択します。</span><span class="sxs-lookup"><span data-stu-id="fba66-181">Before you press **Enter**, select the **Include comments** checkbox in the **Rename** pop-up box.</span></span>

   ![[名前の変更] ダイアログ ボックス](media/tutorial-rename.png)

1. <span data-ttu-id="fba66-183">**Enter** キーを押します。</span><span class="sxs-lookup"><span data-stu-id="fba66-183">Press **Enter**.</span></span>

   <span data-ttu-id="fba66-184">`words` の出現箇所とコード コメント内の `words` への参照箇所の両方で名前が変更されました。</span><span class="sxs-lookup"><span data-stu-id="fba66-184">Both occurrences of `words` have been renamed, as well as the reference to `words` in the code comment.</span></span>

## <a name="next-steps"></a><span data-ttu-id="fba66-185">次の手順</span><span class="sxs-lookup"><span data-stu-id="fba66-185">Next steps</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="fba66-186">プロジェクトとソリューションについて学習する</span><span class="sxs-lookup"><span data-stu-id="fba66-186">Learn about projects and solutions</span></span>](../get-started/tutorial-projects-solutions.md)

## <a name="see-also"></a><span data-ttu-id="fba66-187">関連項目</span><span class="sxs-lookup"><span data-stu-id="fba66-187">See also</span></span>

- [<span data-ttu-id="fba66-188">コード スニペット</span><span class="sxs-lookup"><span data-stu-id="fba66-188">Code snippets</span></span>](../ide/code-snippets.md)
- [<span data-ttu-id="fba66-189">コード間の移動</span><span class="sxs-lookup"><span data-stu-id="fba66-189">Navigate code</span></span>](../ide/navigating-code.md)
- [<span data-ttu-id="fba66-190">アウトライン</span><span class="sxs-lookup"><span data-stu-id="fba66-190">Outlining</span></span>](../ide/outlining.md)
- <span data-ttu-id="fba66-191">[[定義へ移動] と [定義をここに表示]](../ide/go-to-and-peek-definition.md)</span><span class="sxs-lookup"><span data-stu-id="fba66-191">[Go To Definition and Peek Definition](../ide/go-to-and-peek-definition.md)</span></span>
- [<span data-ttu-id="fba66-192">リファクタリング</span><span class="sxs-lookup"><span data-stu-id="fba66-192">Refactoring</span></span>](../ide/refactoring-in-visual-studio.md)
- [<span data-ttu-id="fba66-193">IntelliSense を使用する</span><span class="sxs-lookup"><span data-stu-id="fba66-193">Use IntelliSense</span></span>](../ide/using-intellisense.md)