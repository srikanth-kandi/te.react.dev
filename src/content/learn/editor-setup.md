---
title: ఎడిటర్ సెటప్
---

<Intro>

మీ ఎడిటర్‌ని ప్రొపెర్గా కాన్ఫిగర్ చేయడం వలన మీ కోడ్ ను సులభంగా చదవచ్చు మరియు వేగంగా కూడా వ్రాయవచ్చు. అదనంగా, మీరు కోడ్ను వ్రాస్తున్నప్పుడు బగ్‌లను గుర్తించడంలో ఇది మీకు సహాయపడుతుంది! మీరు ఎడిటర్‌ని సెటప్ చేయడం ఇదే మొదటిసారి అయితే లేదా మీరు మీ ప్రస్తుత ఎడిటర్‌ని ట్యూన్ అప్ చేయాలని అనుకొంటే, మేము వీటిని సిఫార్సు చేస్తాము.

</Intro>

<YouWillLearn>

* అత్యంత ప్రజాదరణ పొందిన ఎడిటర్లు ఏమిటి
* మీ కోడ్‌ను ఆటోమేటిక్ గా ఎలా ఫార్మాట్ చేయాలి

</YouWillLearn>

## మీ ఎడిటర్ {/*your-editor*/}

నేడు వాడుకలో ఉన్న అత్యంత ప్రజాదరణ పొందిన ఎడిటర్లలో [VS Code](https://code.visualstudio.com/) ఒకటి. ఇది ఎక్సటెన్షన్స్ యొక్క పెద్ద మార్కెట్‌ప్లేస్‌ను కలిగి ఉంది మరియు GitHub వంటి పాపులర్ సర్వీసులతో బాగా ఇంటిగ్రేట్ అవుతుంది. దిగువ జాబితా చేయబడిన చాలా ఫీచర్లను VS Code కి ఎక్సటెన్షన్స్ లాగా కూడా జోడించవచ్చు, తద్వారా దీన్ని చాలా వరకు కాన్ఫిగర్ చేయవచ్చు!

React కమ్యూనిటీలో ఉపయోగించే ఇతర పాపులర్ టెక్స్ట్ ఎడిటర్‌లు:

* [WebStorm](https://www.jetbrains.com/webstorm/) అనేది JavaScript కోసం ప్రత్యేకంగా రూపొందించబడిన ఇంటిగ్రేటెడ్ డెవలప్మెంట్ ఎన్విరాన్మెంట్.
* [Sublime Text](https://www.sublimetext.com/) ‌లో JSX మరియు TypeScript కోసం [సింటాక్స్ హైలైటింగ్](https://stackoverflow.com/a/70960574/458193) మరియు ఆటోకంప్లీట్ ఫీచర్లకు బిల్ట్ ఇన్ సపోర్ట్ ఉంది.
* [Vim](https://www.vim.org/) అనేది అత్యంత కాన్ఫిగర్ చేయగల టెక్స్ట్ ఎడిటర్, ఇది ఎలాంటి టెక్స్ట్‌ని అయినా సృష్టించడం మరియు మార్చడం చాలా ఎఫిసియెంట్గా చేయడానికి నిర్మించబడింది. ఇది చాలా UNIX సిస్టమ్‌లతో మరియు Apple OS X తో "vi" గా ఇంక్లూడ్ చేయబడింది.

## సిఫార్సు చేయబడిన టెక్స్ట్ ఎడిటర్ ఫీచర్లు {/*recommended-text-editor-features*/}

కొన్ని ఎడిటర్లకు ఈ ఫీచర్లు బిల్ట్ ఇన్ గా ఉంటాయి, కానీ మరికొన్ని ఎడిటర్లకు వీటిని ఎక్సటెన్షన్స్ లాగా జోడించవలసి ఉంటుంది. మీరు ఉపయోగించాలనుకుంటున్న ఎడిటర్ యొక్క సపోర్ట్ స్టేటస్ని చెక్ చేయండి!

### లింటింగ్ {/*linting*/}

కోడ్ లింటర్‌లు మీరు వ్రాస్తునపుడు మీ కోడ్‌ లోని సమస్యలను కనుగొంటాయి, వాటిని త్వరగా పరిష్కరించడంలో మీకు సహాయపడతాయి. [ESLint](https://eslint.org/) అనేది JavaScript కోసం ఒక పాపులర్, ఓపెన్ సోర్స్ లింటర్. 

* [React కోసం సిఫార్సు చేయబడిన కాన్ఫిగరేషన్‌తో ESLint ని ఇన్‌స్టాల్ చేయండి](https://www.npmjs.com/package/eslint-config-react-app) (మీరు [Node ని ఇన్‌స్టాల్ చేశారని](https://nodejs.org/en/download/current/) నిర్ధారించుకోండి!)
* [అధికారిక ఎక్సటెన్షన్లతో VSCode లో ESLint ను ఇంటిగ్రేట్ చేయండి](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

**మీరు మీ ప్రాజెక్ట్ కోసం అన్ని [`eslint-plugin-react-hooks`](https://www.npmjs.com/package/eslint-plugin-react-hooks) రూల్స్ ను ఎనేబుల్ చేసారని నిర్ధారించుకోండి.** ఇది చాలా ముఖ్యమైనది మరియు చాలా తీవ్రమైన బగ్లను ముందస్తుగా గుర్తించడానికి సహాయపడుతుంది. సిఫార్సు చేయబడిన [`eslint-config-react-app`](https://www.npmjs.com/package/eslint-config-react-app) ప్రీసెట్ ఇప్పటికే వీటిని కలిగి ఉంది.

### ఫార్మాటింగ్ {/*formatting*/}

మీ కోడ్‌ని మరొక కంట్రిబ్యూటర్‌తో షేర్ చేస్తున్నప్పుడు మీరు చివరిగా చేయాల్సింది [ట్యాబ్‌లు vs స్పేస్‌ల](https://www.google.com/search?q=tabs+vs+spaces) గురించి చర్చలో పాల్గొనడం! అదృష్టవశాత్తూ, [Prettier](https://prettier.io/) ప్రీసెట్ రూల్స్ ప్రకారం మీ కోడ్‌ని రీఫార్మాట్ చేయడం ద్వారా దాన్ని క్లీన్ చేయడంలో సహాయపడుతుంది. Prettier ని రన్ చేయండి మరియు మీ ట్యాబ్‌లన్నీ స్పేస్‌లుగా మార్చబడతాయి-మరియు మీ ఇండెంటేషన్, కోట్‌లు మొదలైనవి కూడా కాన్ఫిగరేషన్‌కు అనుగుణంగా మార్చబడతాయి. ఐడియల్ సెటప్‌లో, మీరు మీ ఫైల్‌ను సేవ్ చేసినప్పుడు Prettier రన్ అవుతుంది, మీ కోసం ఈ ఎడిట్లను త్వరగా చేస్తుంది.

మీరు ఈ స్టెప్స్ ను అనుసరించడం ద్వారా [VSCode లో Prettier ఎక్స్టెన్షన్](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) ను ఇన్‌స్టాల్ చేయవచ్చు:

1. VS Code ని స్టార్ట్ చేయండి
2. Quick Open ని ఉపయోగించండి (Ctrl/Cmd+P ని ప్రెస్ చేయండి)
3. `ext install esbenp.prettier-vscode` ని పేస్ట్ చేయండి
4. Enter ని ప్రెస్ చేయండి

#### సేవ్ చేస్తున్నప్పుడు ఫార్మాట్ చేయడం {/*formatting-on-save*/}

ఐడీఎల్ గా, మీరు ప్రతి సేవ్‌లో మీ కోడ్‌ను ఫార్మాట్ చేయాలి. VS Code దీనికి సెట్టింగ్‌లను కలిగి ఉంది!

1. VS Code లో, `CTRL/CMD + SHIFT + P` ని ప్రెస్ చేయండి.
2. "settings" అని టైప్ చేయండి
3. Enter ని ప్రెస్ చేయండి
4. సెర్చ్ బార్లో, "format on save" అని టైప్ చేయండి
5. "format on save" ఆప్షన్ ని టిక్ చేశారని నిర్ధారించుకోండి!

> మీ ESLint ప్రీసెట్ ఫార్మాటింగ్ రూల్స్ ను కలిగి ఉంటే, అవి Prettier తో కాన్ఫ్లిక్ట్ అవచ్చు. [`eslint-config-prettier`](https://github.com/prettier/eslint-config-prettier) ని ఉపయోగించి మీ ESLint ప్రీసెట్‌లోని అన్ని ఫార్మాటింగ్ రూల్స్ ను డిసేబుల్ చేయమని మేము సిఫార్సు చేస్తున్నాము, తద్వారా ESLint లాజికల్ తప్పులను గుర్తించడానికి *మాత్రమే* ఉపయోగించబడుతుంది. పుల్ రిక్వెస్ట్ ని మెర్జ్ చేయడానికి ముందు ఫైల్‌లు ఫార్మాట్ చేయడం ని మీరు అమలు చేయాలనుకుంటే, మీ కన్తినుఔస్ ఇంటిగ్రేషన్ (CI) కోసం [`prettier --check`](https://prettier.io/docs/en/cli.html#--check) ని ఉపయోగించండి.
