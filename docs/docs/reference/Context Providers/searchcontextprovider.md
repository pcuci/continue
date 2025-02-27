import ClassPropertyRef from '@site/src/components/ClassPropertyRef.tsx';

# SearchContextProvider

Type '@search' to reference the results of codebase search, just like the results you would get from VS Code search.

[View the source](https://github.com/continuedev/continue/blob/main/server/continuedev/libs/llm/plugins/context_providers/search.py)

## Properties

<ClassPropertyRef name='workspace_dir' details='{&quot;title&quot;: &quot;Workspace Dir&quot;, &quot;description&quot;: &quot;The workspace directory to search&quot;, &quot;type&quot;: &quot;string&quot;}' required={false} default=""/>


### Inherited Properties

<ClassPropertyRef name='title' details='{&quot;title&quot;: &quot;Title&quot;, &quot;default&quot;: &quot;search&quot;, &quot;type&quot;: &quot;string&quot;}' required={false} default="search"/>
<ClassPropertyRef name='ide' details='{&quot;title&quot;: &quot;Ide&quot;}' required={false} default=""/>
<ClassPropertyRef name='display_title' details='{&quot;title&quot;: &quot;Display Title&quot;, &quot;default&quot;: &quot;Search&quot;, &quot;type&quot;: &quot;string&quot;}' required={false} default="Search"/>
<ClassPropertyRef name='description' details='{&quot;title&quot;: &quot;Description&quot;, &quot;default&quot;: &quot;Search workspace for exact matches&quot;, &quot;type&quot;: &quot;string&quot;}' required={false} default="Search workspace for exact matches"/>
<ClassPropertyRef name='dynamic' details='{&quot;title&quot;: &quot;Dynamic&quot;, &quot;default&quot;: true, &quot;type&quot;: &quot;boolean&quot;}' required={false} default="True"/>
<ClassPropertyRef name='requires_query' details='{&quot;title&quot;: &quot;Requires Query&quot;, &quot;default&quot;: true, &quot;type&quot;: &quot;boolean&quot;}' required={false} default="True"/>
