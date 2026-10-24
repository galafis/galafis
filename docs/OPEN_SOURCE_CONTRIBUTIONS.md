# Open-source contribution evidence · Evidências de contribuições

**53 pull requests · 32 projects / projetos**

**EN:** A record of focused corrections, executable examples and regression tests across scientific computing, finance, data workflows and software infrastructure. Each pull request links the implementation, review and current CI results. This index includes seven earlier submissions and the subsequent expanded batch.

**PT:** Registro de correções focadas, exemplos executáveis e testes de regressão em computação científica, finanças, fluxos de dados e infraestrutura de software. Cada pull request reúne implementação, revisão e resultados atuais de CI. O índice inclui sete envios anteriores e a etapa ampliada de contribuições.

[Profile · Perfil](https://github.com/galafis) · [Structured validation · Validação estruturada](contributions.json)

## Review and validation · Revisão e validação

**EN:** Test summaries describe the environment and scope actually exercised. Approvals, pending workflows and merge decisions remain visible in the linked projects. The two Dask proposals remain drafts awaiting the author review required by that project.

**PT:** Os resumos de testes registram o ambiente e o escopo efetivamente executados. Aprovações, verificações pendentes e decisões de incorporação ficam disponíveis nos projetos vinculados. As duas propostas ao Dask permanecem como rascunhos, aguardando a revisão pessoal exigida pelo projeto.

**Follow-up · Acompanhamento:** [NeuroKit #1228](https://github.com/neuropsychology/NeuroKit/pull/1228) was corrected for pandas 2/3 and its Python 3.10–3.14 matrix passed. [Pmdarima #627](https://github.com/alkaline-ml/pmdarima/pull/627) addresses the shared pipeline failure in [#625](https://github.com/alkaline-ml/pmdarima/pull/625)/[#626](https://github.com/alkaline-ml/pmdarima/pull/626); its Python 3.10–3.14, lint and documentation CI passed. Dask CI details and the existing [fixture proposal #12671](https://github.com/dask/dask/pull/12671) are recorded in both draft descriptions. / O NeuroKit #1228 recebeu a correção para pandas 2/3 e passou na matriz Python 3.10–3.14. O pmdarima #627 corrige a falha compartilhada do pipeline de #625/#626 e passou no CI de Python 3.10–3.14, lint e documentação. As descrições dos dois rascunhos Dask registram o diagnóstico de CI e a proposta existente para a fixture.

**Merged upstream · Incorporado ao projeto:** [bashtage/arch #975](https://github.com/bashtage/arch/pull/975)

<a id="science-health"></a>

## Science and health · Ciência e saúde

| Project · Projeto | Change · Correção | Code · Código | Review · Revisão |
| --- | --- | --- | --- |
| nipy/nibabel | Avoid integer overflow when computing voxel sizes | [PR #1586](https://github.com/nipy/nibabel/pull/1586) · [fc8fdc0](https://github.com/nipy/nibabel/commit/fc8fdc0255e0eacb402a895980c5bf8d321a12fd) · [Tests · Testes](#evidence-nipy-nibabel-1586) | Open · Aberto |
| CamDavidsonPilon/lifelines | Correct the censored subject in the survival-table example | [PR #1708](https://github.com/CamDavidsonPilon/lifelines/pull/1708) · [80399b3](https://github.com/CamDavidsonPilon/lifelines/commit/80399b33c774ae9e90434c5d97fe682b7dd06000) · [Tests · Testes](#evidence-camdavidsonpilon-lifelines-1708) | Open · Aberto |
| CamDavidsonPilon/lifelines | Shuffle cross-validation rows by position to support duplicate indices | [PR #1710](https://github.com/CamDavidsonPilon/lifelines/pull/1710) · [b1f5821](https://github.com/CamDavidsonPilon/lifelines/commit/b1f582175346139383c59949fd1ee813847359bd) · [Tests · Testes](#evidence-camdavidsonpilon-lifelines-1710) | Open · Aberto |
| CamDavidsonPilon/lifelines | Use observation ranks in the complete-separation correlation check | [PR #1711](https://github.com/CamDavidsonPilon/lifelines/pull/1711) · [2a2cb92](https://github.com/CamDavidsonPilon/lifelines/commit/2a2cb920d58f156e79904dbe3de8044eb71a14b5) · [Tests · Testes](#evidence-camdavidsonpilon-lifelines-1711) | Open · Aberto |
| CamDavidsonPilon/lifelines | Evaluate the default observation cutoff when converting durations | [PR #1712](https://github.com/CamDavidsonPilon/lifelines/pull/1712) · [d3d2c62](https://github.com/CamDavidsonPilon/lifelines/commit/d3d2c62f4ef97a9500b5af7ee22dbfc64498ec9b) · [Tests · Testes](#evidence-camdavidsonpilon-lifelines-1712) | Open · Aberto |
| CamDavidsonPilon/lifelines | Keep single-row survival DataFrames as Series for quantile lookup | [PR #1713](https://github.com/CamDavidsonPilon/lifelines/pull/1713) · [9556d05](https://github.com/CamDavidsonPilon/lifelines/commit/9556d0567c1c344cd66d737a5d8537073591a721) · [Tests · Testes](#evidence-camdavidsonpilon-lifelines-1713) | Open · Aberto |
| neuropsychology/NeuroKit | Apply monotone interpolation fill values at actual data boundaries | [PR #1227](https://github.com/neuropsychology/NeuroKit/pull/1227) · [5564aa1](https://github.com/neuropsychology/NeuroKit/commit/5564aa19e317c7ca6ee6e4871b023aa1a6c59732) · [Tests · Testes](#evidence-neuropsychology-neurokit-1227) | Open · Aberto |
| neuropsychology/NeuroKit | Preserve pandas labels during rolling standardization | [PR #1228](https://github.com/neuropsychology/NeuroKit/pull/1228) · [cd066e1](https://github.com/neuropsychology/NeuroKit/commit/cd066e1c41f3ead81238f68d6eec8d93514c1009) · [Tests · Testes](#evidence-neuropsychology-neurokit-1228) | Open · Aberto |
| nipy/nibabel | Exclude complex infinities from finite_range | [PR #1588](https://github.com/nipy/nibabel/pull/1588) · [a9bf7b8](https://github.com/nipy/nibabel/commit/a9bf7b8bdbfe27a3bfd2131d581341870ef2685b) · [Tests · Testes](#evidence-nipy-nibabel-1588) | Open · Aberto |
| pydicom/pydicom | Serialize buffered binary element values to JSON | [PR #2409](https://github.com/pydicom/pydicom/pull/2409) · [de6b131](https://github.com/pydicom/pydicom/commit/de6b1315a388b977d0f9ffd459bd7e7a05c34fb6) · [Tests · Testes](#evidence-pydicom-pydicom-2409) | Open · Aberto |
| neuropsychology/NeuroKit | Scale robust standardization by each column MAD | [PR #1229](https://github.com/neuropsychology/NeuroKit/pull/1229) · [f3b705a](https://github.com/neuropsychology/NeuroKit/commit/f3b705a84e47516f3bec66cf6e3e47e5594b6fbd) · [Tests · Testes](#evidence-neuropsychology-neurokit-1229) | Open · Aberto |
| pydicom/pydicom | Restore buffer positions when context operations raise | [PR #2410](https://github.com/pydicom/pydicom/pull/2410) · [76f4a33](https://github.com/pydicom/pydicom/commit/76f4a335f0dc6a9c24ef76b46ec3394651f6bd51) · [Tests · Testes](#evidence-pydicom-pydicom-2410) | Open · Aberto |
| imageio/imageio | Match planar DICOM pixel byte order to the transfer syntax | [PR #1250](https://github.com/imageio/imageio/pull/1250) · [0b43068](https://github.com/imageio/imageio/commit/0b430681f18b42b15d3b21e8647ce392e4de37da) · [Tests · Testes](#evidence-imageio-imageio-1250) | Open · Aberto |
| mhe/pynrrd | Reject truncated compressed NRRD payloads | [PR #174](https://github.com/mhe/pynrrd/pull/174) · [2fe3cda](https://github.com/mhe/pynrrd/commit/2fe3cda2b9023b8f418190969c5f952e7ee0ea9a) · [Tests · Testes](#evidence-mhe-pynrrd-174) | Open · Aberto |
| mhe/pynrrd | Apply positive byte skips after decompression | [PR #175](https://github.com/mhe/pynrrd/pull/175) · [2e322ef](https://github.com/mhe/pynrrd/commit/2e322ef16cc6403efa7e7592c92eeb172b1e4b85) · [Tests · Testes](#evidence-mhe-pynrrd-175) | Open · Aberto |
| pydata/patsy | Accept single-pass iterables in LinearConstraint.combine | [PR #277](https://github.com/pydata/patsy/pull/277) · [9ac1fe5](https://github.com/pydata/patsy/commit/9ac1fe5fb1ecfa1afc65dae545c47516e22a031e) · [Tests · Testes](#evidence-pydata-patsy-277) | Open · Aberto |

<a id="finance"></a>

## Finance and numerical accuracy · Finanças e precisão numérica

| Project · Projeto | Change · Correção | Code · Código | Review · Revisão |
| --- | --- | --- | --- |
| PyPortfolio/PyPortfolioOpt | Preserve caller benchmark columns in CAPM return estimates | [PR #772](https://github.com/PyPortfolio/PyPortfolioOpt/pull/772) · [dc50cc0](https://github.com/PyPortfolio/PyPortfolioOpt/commit/dc50cc0a6a67e0dfc868be80b9620e110dbed8e6) · [Tests · Testes](#evidence-pyportfolio-pyportfolioopt-772) | Open · Aberto |
| bashtage/arch | Preserve small upper-tail Wald p-values | [PR #975](https://github.com/bashtage/arch/pull/975) · [806d630](https://github.com/bashtage/arch/commit/806d630ed84039354cecec9f6f1470c71e67c0fe) · [Tests · Testes](#evidence-bashtage-arch-975) | Merged · Incorporado |
| bashtage/arch | Preserve NumPy complex scalars in object data | [PR #976](https://github.com/bashtage/arch/pull/976) · [7209098](https://github.com/bashtage/arch/commit/720909801729a74cfcb61faf96494761d575c124) · [Tests · Testes](#evidence-bashtage-arch-976) | Open · Aberto |
| dcajasn/Riskfolio-Lib | Return zero range for a single observation | [PR #269](https://github.com/dcajasn/Riskfolio-Lib/pull/269) · [9d9d3d4](https://github.com/dcajasn/Riskfolio-Lib/commit/9d9d3d46bf63c0ceb158e8de91c5ad5ddea109ac) · [Tests · Testes](#evidence-dcajasn-riskfolio-lib-269) | Open · Aberto |
| dcajasn/Riskfolio-Lib | Avoid exponential overflow in entropic risk calculations | [PR #270](https://github.com/dcajasn/Riskfolio-Lib/pull/270) · [a481c28](https://github.com/dcajasn/Riskfolio-Lib/commit/a481c2891eade026fda27cee68b34bedc632e3d2) · [Tests · Testes](#evidence-dcajasn-riskfolio-lib-270) | Open · Aberto |
| kernc/backtesting.py | Report total loss in geometric mean returns | [PR #1429](https://github.com/kernc/backtesting.py/pull/1429) · [9a9c603](https://github.com/kernc/backtesting.py/commit/9a9c603a26b260982a1480bd05628bdfadb773b5) · [Tests · Testes](#evidence-kernc-backtesting-py-1429) | Open · Aberto |
| alkaline-ml/pmdarima | Preserve Box-Cox precision for lambda near zero | [PR #625](https://github.com/alkaline-ml/pmdarima/pull/625) · [8052b36](https://github.com/alkaline-ml/pmdarima/commit/8052b36f271bf8f7ecc097da436867d1dd06ddca) · [Tests · Testes](#evidence-alkaline-ml-pmdarima-625) | Open · Aberto |
| alkaline-ml/pmdarima | Keep perfect zero-valued forecasts finite in SMAPE | [PR #626](https://github.com/alkaline-ml/pmdarima/pull/626) · [857f394](https://github.com/alkaline-ml/pmdarima/commit/857f394452d580ef30260b9b0ce35bdac2c2e4d5) · [Tests · Testes](#evidence-alkaline-ml-pmdarima-626) | Open · Aberto |
| alkaline-ml/pmdarima | Copy pipeline confidence intervals before inverse transformation | [PR #627](https://github.com/alkaline-ml/pmdarima/pull/627) · [f15a6dd](https://github.com/alkaline-ml/pmdarima/commit/f15a6dd0a4413152cb84452532522bd5cd9b6a0c) · [Tests · Testes](#evidence-alkaline-ml-pmdarima-627) | Open · Aberto |
| bashtage/arch | Preserve small normal-tail p-values | [PR #977](https://github.com/bashtage/arch/pull/977) · [77a7f0c](https://github.com/bashtage/arch/commit/77a7f0c4b353a9076327e077b7001b93efac8de6) · [Tests · Testes](#evidence-bashtage-arch-977) | Open · Aberto |

<a id="signals"></a>

## Signals and time series · Sinais e séries temporais

| Project · Projeto | Change · Correção | Code · Código | Review · Revisão |
| --- | --- | --- | --- |
| rlabbe/filterpy | Accept array-like means in SimplexSigmaPoints | [PR #334](https://github.com/rlabbe/filterpy/pull/334) · [5dcb359](https://github.com/rlabbe/filterpy/commit/5dcb359f5f481e61da1d71cc58cd5e80504a73a0) · [Tests · Testes](#evidence-rlabbe-filterpy-334) | Open · Aberto |
| rlabbe/filterpy | Fix standalone RTS smoothing with varying transition and noise matrices | [PR #335](https://github.com/rlabbe/filterpy/pull/335) · [8b20d7a](https://github.com/rlabbe/filterpy/commit/8b20d7a0022a283c4a48aad78937e040cf9edfcf) · [Tests · Testes](#evidence-rlabbe-filterpy-335) | Open · Aberto |
| unit8co/darts | Fix scalar division by TimeSeries | [PR #3298](https://github.com/unit8co/darts/pull/3298) · [dc35491](https://github.com/unit8co/darts/commit/dc35491da62f1a034136ad5705d85a61df944e7e) · [Tests · Testes](#evidence-unit8co-darts-3298) | Open · Aberto |
| blue-yonder/tsfresh | Preserve integer distances in sample and approximate entropy | [PR #1138](https://github.com/blue-yonder/tsfresh/pull/1138) · [cb356a2](https://github.com/blue-yonder/tsfresh/commit/cb356a2d147333e1a4cb6e6fe2171ee3d5894ecd) · [Tests · Testes](#evidence-blue-yonder-tsfresh-1138) | Open · Aberto |
| rlabbe/filterpy | Fix the scale of rand_student_t samples | [PR #336](https://github.com/rlabbe/filterpy/pull/336) · [a396dd3](https://github.com/rlabbe/filterpy/commit/a396dd3b3dfed921d65fea19336151d0e87a2087) · [Tests · Testes](#evidence-rlabbe-filterpy-336) | Open · Aberto |
| rlabbe/filterpy | Support flat state vectors in sequential Kalman updates | [PR #337](https://github.com/rlabbe/filterpy/pull/337) · [f904811](https://github.com/rlabbe/filterpy/commit/f904811d7e442de190ec963f4bbbc1d420321cc1) · [Tests · Testes](#evidence-rlabbe-filterpy-337) | Open · Aberto |
| rlabbe/filterpy | Use predicted mode probabilities when combining IMM priors | [PR #338](https://github.com/rlabbe/filterpy/pull/338) · [6982255](https://github.com/rlabbe/filterpy/commit/6982255393817ba41d79923e5d51a4a3d0ae85b7) · [Tests · Testes](#evidence-rlabbe-filterpy-338) | Open · Aberto |

<a id="data-ml"></a>

## Data workflows and machine learning · Dados e aprendizado de máquina

| Project · Projeto | Change · Correção | Code · Código | Review · Revisão |
| --- | --- | --- | --- |
| koaning/scikit-lego | Fix log_step shape deltas for keyword dataframe arguments | [PR #846](https://github.com/koaning/scikit-lego/pull/846) · [fa9aef4](https://github.com/koaning/scikit-lego/commit/fa9aef4e22111cee74d3873776c3e8224941410b) · [Tests · Testes](#evidence-koaning-scikit-lego-846) | Open · Aberto |
| dask/dask | Avoid observed warnings in categorical variance aggregation | [PR #12673](https://github.com/dask/dask/pull/12673) · [6dd6d7b](https://github.com/dask/dask/commit/6dd6d7ba47d258de61cdecd3700457ddd111e397) · [Tests · Testes](#evidence-dask-dask-12673) | Draft · Rascunho |
| dask/dask | Preserve falsy column names in variance aggregation | [PR #12674](https://github.com/dask/dask/pull/12674) · [0a829f2](https://github.com/dask/dask/commit/0a829f2df1bfdc29fb9c632e32b797b5c2de98e5) · [Tests · Testes](#evidence-dask-dask-12674) | Draft · Rascunho |
| scikit-learn-contrib/imbalanced-learn | Validate per-class RandomOverSampler shrinkage factors | [PR #1239](https://github.com/scikit-learn-contrib/imbalanced-learn/pull/1239) · [34f310c](https://github.com/scikit-learn-contrib/imbalanced-learn/commit/34f310ca69c4aab01c4f42d7b1c40a039076f4c5) · [Tests · Testes](#evidence-scikit-learn-contrib-imbalanced-learn-1239) | Open · Aberto |
| pydata/xarray | Fix Windows Zarr directory detection in open_dataset | [PR #11802](https://github.com/pydata/xarray/pull/11802) · [c849556](https://github.com/pydata/xarray/commit/c8495566c7a4067dd6a692af8aa281970f393311) · [Tests · Testes](#evidence-pydata-xarray-11802) | Open · Aberto |
| pytoolz/toolz | Make sliding_window startup linear in the window size | [PR #655](https://github.com/pytoolz/toolz/pull/655) · [3631498](https://github.com/pytoolz/toolz/commit/36314982a66463486899b76f9c7183c8c4ec5526) · [Tests · Testes](#evidence-pytoolz-toolz-655) | Open · Aberto |

<a id="software-access"></a>

## Software, communication and accessibility · Software, comunicação e acessibilidade

| Project · Projeto | Change · Correção | Code · Código | Review · Revisão |
| --- | --- | --- | --- |
| pa11y/pa11y-ci | Show actionable CLI output with a reproducible sample page | [PR #377](https://github.com/pa11y/pa11y-ci/pull/377) · [940b7d2](https://github.com/pa11y/pa11y-ci/commit/940b7d2032d4b8ad265d0c15722876034773a00b) · [Tests · Testes](#evidence-pa11y-pa11y-ci-377) | Open · Aberto |
| marshmallow-code/apispec | Reject duplicate names for unreferenced lazy components | [PR #1088](https://github.com/marshmallow-code/apispec/pull/1088) · [9553704](https://github.com/marshmallow-code/apispec/commit/9553704dbd3f0b2c85e677721b47613e34b88a28) · [Tests · Testes](#evidence-marshmallow-code-apispec-1088) | Open · Aberto |
| marshmallow-code/apispec | Keep custom field mappings local to each plugin | [PR #1089](https://github.com/marshmallow-code/apispec/pull/1089) · [f17c0a8](https://github.com/marshmallow-code/apispec/commit/f17c0a82974aa7903c1c8bdf618ca9b4492ec2ce) · [Tests · Testes](#evidence-marshmallow-code-apispec-1089) | Open · Aberto |
| micheles/decorator | Preserve the signature of partials when decorating them | [PR #195](https://github.com/micheles/decorator/pull/195) · [f33bfa8](https://github.com/micheles/decorator/commit/f33bfa8f18f0e02ee653abbec83243397c8e2f0f) · [Tests · Testes](#evidence-micheles-decorator-195) | Open · Aberto |
| micheles/decorator | Preserve positional-only parameters in decoratorx | [PR #196](https://github.com/micheles/decorator/pull/196) · [08b372c](https://github.com/micheles/decorator/commit/08b372c9017845c7adcabdf8253096b248c869ad) · [Tests · Testes](#evidence-micheles-decorator-196) | Open · Aberto |
| jazzband/tablib | Clear stale column configuration when wiping a Dataset | [PR #710](https://github.com/jazzband/tablib/pull/710) · [7118e70](https://github.com/jazzband/tablib/commit/7118e7005cc669aa55be870fb7e3fac043af8d8a) · [Tests · Testes](#evidence-jazzband-tablib-710) | Open · Aberto |
| getsentry/responses | Distinguish JSON booleans from numbers in request matching | [PR #842](https://github.com/getsentry/responses/pull/842) · [943b9e9](https://github.com/getsentry/responses/commit/943b9e983d804c6b38eb82039462f31d8e175739) · [Tests · Testes](#evidence-getsentry-responses-842) | Open · Aberto |
| Pylons/webob | Make MultiDict.setdefault return the current value of duplicate keys | [PR #504](https://github.com/Pylons/webob/pull/504) · [e4174c7](https://github.com/Pylons/webob/commit/e4174c7560aff635c0ab97f74267ed0cd869da9d) · [Tests · Testes](#evidence-pylons-webob-504) | Open · Aberto |
| pyserial/pyserial | Honor the total read timeout in the loopback handler | [PR #886](https://github.com/pyserial/pyserial/pull/886) · [47fc2e7](https://github.com/pyserial/pyserial/commit/47fc2e7586137ecfacc5588bde6d8197cc824218) · [Tests · Testes](#evidence-pyserial-pyserial-886) | Open · Aberto |
| websocket-client/websocket-client | Accept case-insensitive WebSocket URL schemes | [PR #1082](https://github.com/websocket-client/websocket-client/pull/1082) · [b555851](https://github.com/websocket-client/websocket-client/commit/b55585106f1fca8e36d084dd1eea2f5dc02c3dac) · [Tests · Testes](#evidence-websocket-client-websocket-client-1082) | Open · Aberto |
| GrahamDumpleton/wrapt | Preserve variadic annotations in formatargspec | [PR #363](https://github.com/GrahamDumpleton/wrapt/pull/363) · [33b779d](https://github.com/GrahamDumpleton/wrapt/commit/33b779df4c0bee145a506e0bc3edaa991e8c2c7b) · [Tests · Testes](#evidence-grahamdumpleton-wrapt-363) | Open · Aberto |
| requests/toolbelt | Fall back from unknown response encodings | [PR #412](https://github.com/requests/toolbelt/pull/412) · [d28289b](https://github.com/requests/toolbelt/commit/d28289b9693471adb66bbc5602e92d13b611d2aa) · [Tests · Testes](#evidence-requests-toolbelt-412) | Open · Aberto |
| c0fec0de/anytree | Honor false-valued parents in sibling helpers | [PR #285](https://github.com/c0fec0de/anytree/pull/285) · [13b3988](https://github.com/c0fec0de/anytree/commit/13b39883956d295aa28506b9b49d41f589a99e70) · [Tests · Testes](#evidence-c0fec0de-anytree-285) | Open · Aberto |
| gorakhargosh/watchdog | Deduplicate consecutive None items in SkipRepeatsQueue | [PR #1348](https://github.com/gorakhargosh/watchdog/pull/1348) · [50e15e6](https://github.com/gorakhargosh/watchdog/commit/50e15e67882da612b9d76f36081e9598005729d3) · [Tests · Testes](#evidence-gorakhargosh-watchdog-1348) | Open · Aberto |

## Validation records · Registros de validação

<a id="evidence-koaning-scikit-lego-846"></a>

<details>
<summary>koaning/scikit-lego #846 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/koaning/scikit-lego/pull/846/files)

40 pandas utility tests; Ruff 0.15.11 check sklego tests; changed source format; executable documentation snippet

</details>

<a id="evidence-pa11y-pa11y-ci-377"></a>

<details>
<summary>pa11y/pa11y-ci #377 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/pa11y/pa11y-ci/pull/377/files)

Actual browser runs: missing language exit 2, corrected language exit 0; 59 unit tests; lint zero errors with one existing warning

</details>

<a id="evidence-dask-dask-12673"></a>

<details>
<summary>dask/dask #12673 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/dask/dask/pull/12673/files)

Four tests failed before fix; 245 groupby tests pass on pandas 2.2.3, 12 focused tests pass on pandas 3.1.0; pinned Ruff and Black passed.

</details>

<a id="evidence-dask-dask-12674"></a>

<details>
<summary>dask/dask #12674 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/dask/dask/pull/12674/files)

8 failures and 4 passing controls before fix; all 253 groupby tests pass on pandas 2.2.3. On pandas 3.1.0: 249 pass, 2 skip, 2 existing tuple-selection warnings fail, reproduced without this patch. New 12 cases all pass. Pinned Ruff and Black passed.

</details>

<a id="evidence-scikit-learn-contrib-imbalanced-learn-1239"></a>

<details>
<summary>scikit-learn-contrib/imbalanced-learn #1239 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/scikit-learn-contrib/imbalanced-learn/pull/1239/files)

10 regression failures before fix; 117 oversampling tests pass in each environment: scikit-learn 1.4.2 and 1.9.1. Ruff 0.4.8 and Black 23.3.0 pass.

</details>

<a id="evidence-pydata-xarray-11802"></a>

<details>
<summary>pydata/xarray #11802 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/pydata/xarray/pull/11802/files)

6 failures and 6 passing controls before fix; 101 utils/plugin tests passed, 1 skipped (h5netcdf unavailable). 12 additional selected Zarr tests passed, 374 dependency/environment skips. After final type annotations, all 12 focused checks pass. Ruff 0.16.10 lint, format and docstring-preview checks and git diff --check passed.

</details>

<a id="evidence-pytoolz-toolz-655"></a>

<details>
<summary>pytoolz/toolz #655 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/pytoolz/toolz/pull/655/files)

272 tests/doctests passed and 2 skipped on each of CPython 3.9.25 and 3.12.14; both sliding-window benchmark tests pass on both versions. Source passes CI pycodestyle rule set; changed lines pass pycodestyle; git diff --check passes.

</details>

<a id="evidence-pyportfolio-pyportfolioopt-772"></a>

<details>
<summary>PyPortfolio/PyPortfolioOpt #772 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/PyPortfolio/PyPortfolioOpt/pull/772/files)

```json
{
  "before": "2 new cases fail on caller DataFrame column mutation",
  "after": "21 passed in complete tests/test_expected_returns.py",
  "black": "2 files unchanged",
  "diff_check": "passed",
  "limitations": "Full optimization suite not rerun; no model formula change"
}
```

</details>

<a id="evidence-nipy-nibabel-1586"></a>

<details>
<summary>nipy/nibabel #1586 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/nipy/nibabel/pull/1586/files)

```json
{
  "python": "3.12.14",
  "numpy": "2.5.4",
  "scipy": "1.18.1",
  "pytest": "9.1.1",
  "before": "5 failed, 9 passed on base (four signed integer cases and array-like regression)",
  "after": "32 passed across affines, processing and orientations (15 affines tests, including uint8)",
  "lint": "ruff check, ruff format --check and git diff --check passed",
  "full_suite": "Stopped after progress remained at 34% for several minutes; no completed summary, no full-suite claim"
}
```

</details>

<a id="evidence-camdavidsonpilon-lifelines-1708"></a>

<details>
<summary>CamDavidsonPilon/lifelines #1708 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/CamDavidsonPilon/lifelines/pull/1708/files)

```json
{
  "before": "extracted first code block executes; assertion for censored subject 2 fails with True",
  "after": "same check passes with False",
  "python": "3.12.14",
  "pandas": "2.3.3",
  "lifelines": "0.30.3",
  "limitations": "No Sphinx build or full suite; a single literal change in documentation"
}
```

</details>

<a id="evidence-camdavidsonpilon-lifelines-1710"></a>

<details>
<summary>CamDavidsonPilon/lifelines #1710 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/CamDavidsonPilon/lifelines/pull/1710/files)

```json
{
  "before": "3 regressions failed; duplicate and multiindex raise ValueError, constant index produces different CV scores",
  "after": "92 passed in lifelines/tests/utils/test_utils.py, two approximation warnings",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pandas": "2.3.3",
    "lifelines": "0.30.3"
  },
  "full_suite": "Not run; complete utility module exercised",
  "format": "Black 22.8.0, line length 130, reports unchanged baseline formatting differences in both candidate and git-show HEAD controls; no changed-line formatting findings. git diff --check passes."
}
```

</details>

<a id="evidence-camdavidsonpilon-lifelines-1711"></a>

<details>
<summary>CamDavidsonPilon/lifelines #1711 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/CamDavidsonPilon/lifelines/pull/1711/files)

```json
{
  "before": "4 failed negative-correlation regressions; 4 passed positive-correlation controls",
  "after": "97 passed in lifelines/tests/utils/test_utils.py; two approximation warnings",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pandas": "2.3.3",
    "scipy": "1.18.1"
  },
  "format": "git diff --check clean; Black 22.8.0 diff confined to unchanged baseline sections",
  "limitations": "Full model suite not run"
}
```

</details>

<a id="evidence-camdavidsonpilon-lifelines-1712"></a>

<details>
<summary>CamDavidsonPilon/lifelines #1712 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/CamDavidsonPilon/lifelines/pull/1712/files)

```json
{
  "before": "Default-clock regression fails: duration based on import-time date rather than substituted call-time clock",
  "after": "90 passed in lifelines/tests/utils/test_utils.py; two approximation warnings",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pandas": "2.3.3"
  },
  "format": "git diff --check clean; Black22.8.0 diff only unchanged baseline",
  "limitations": "Full model suite not run"
}
```

</details>

<a id="evidence-camdavidsonpilon-lifelines-1713"></a>

<details>
<summary>CamDavidsonPilon/lifelines #1713 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/CamDavidsonPilon/lifelines/pull/1713/files)

```json
{
  "before": "4 new single-row DataFrame cases fail with ValueError while equivalent Series inputs work",
  "after": "93 passed in lifelines/tests/utils/test_utils.py; two approximation warnings",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pandas": "2.3.3"
  },
  "format": "git diff --check clean; Black 22.8.0 differences are unrelated baseline",
  "limitations": "Full model suite not run"
}
```

</details>

<a id="evidence-bashtage-arch-975"></a>

<details>
<summary>bashtage/arch #975 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/bashtage/arch/pull/975/files)

```json
{
  "before": "4 new cases fail; stat50 loses3.8e-6 relative precision, stats100/500/1000 round to0",
  "after": "1227 utility tests passed",
  "limitations": "Full econometric-model suite not run",
  "ruff": "lint and format passed for both files"
}
```

</details>

<a id="evidence-bashtage-arch-976"></a>

<details>
<summary>bashtage/arch #976 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/bashtage/arch/pull/976/files)

```json
{
  "before": "NumPy-complex allowed case loses imaginary component; disallowed case does not raise",
  "after": "485 dtype-policy tests passed; 24 cases span four helpers and ndarray/Series/DataFrame",
  "ruff": "Both files pass lint and format",
  "limitations": "Source tree tested with ignored version metadata from installed arch8.0.0. Full model suite not run."
}
```

</details>

<a id="evidence-dcajasn-riskfolio-lib-269"></a>

<details>
<summary>dcajasn/Riskfolio-Lib #269 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/dcajasn/Riskfolio-Lib/pull/269/files)

```json
{
  "before": "3 failed, 3 passed",
  "after": "6 passed",
  "limitations": "Full optimization suite not run; compiled extension/version metadata supplied by same-version7.4.0 wheel",
  "ruff": "test lint and format passed"
}
```

</details>

<a id="evidence-dcajasn-riskfolio-lib-270"></a>

<details>
<summary>dcajasn/Riskfolio-Lib #270 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/dcajasn/Riskfolio-Lib/pull/270/files)

```json
{
  "before": "6 failed, 2 passed",
  "after": "8 passed",
  "diff_check": "passed",
  "limitations": "Source imports verified. Same-version 7.4.0 wheel supplies ignored compiled extension/version file. Full optimization suite not run; source has existing lint violations."
}
```

</details>

<a id="evidence-kernc-backtesting-py-1429"></a>

<details>
<summary>kernc/backtesting.py #1429 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/kernc/backtesting.py/pull/1429/files)

```json
{
  "before": "4 helper subcases fail, integration reports annualized 0 rather than -100",
  "after": "26 TestBacktest tests pass",
  "flake8": "both changed files passed",
  "diff_check": "passed",
  "limitations": "Existing pandas deprecation warnings. Same 10 mypy errors in unchanged _plotting.py on clean baseline.",
  "full_suite": "84 tests OK, 1 skipped, after installing test extras",
  "mypy": "same 10 _plotting.py errors as clean baseline; error lines identical"
}
```

</details>

<a id="evidence-marshmallow-code-apispec-1088"></a>

<details>
<summary>marshmallow-code/apispec #1088 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/marshmallow-code/apispec/pull/1088/files)

24 regression combinations; 12 fail before fix, all pass after. Full suite 660 passed, 6 skipped. Ruff lint/format pass.

</details>

<a id="evidence-marshmallow-code-apispec-1089"></a>

<details>
<summary>marshmallow-code/apispec #1089 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/marshmallow-code/apispec/pull/1089/files)

Regression fails before; full suite 637 passed, 6 skipped after. Ruff and diff checks pass.

</details>

<a id="evidence-micheles-decorator-195"></a>

<details>
<summary>micheles/decorator #195 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/micheles/decorator/pull/195/files)

New regression fails before fix; 29 tests pass after on Python 3.12.14. git diff --check passes.

</details>

<a id="evidence-micheles-decorator-196"></a>

<details>
<summary>micheles/decorator #196 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/micheles/decorator/pull/196/files)

New regression fails before fix; 29 tests pass after on Python 3.12.14. git diff --check passes.

</details>

<a id="evidence-neuropsychology-neurokit-1227"></a>

<details>
<summary>neuropsychology/NeuroKit #1227 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/neuropsychology/NeuroKit/pull/1227/files)

```json
{
  "before": "6 failed boundary-fill cases, 2 passed extrapolation controls; initial focused command also hits whole-package coverage threshold by design",
  "after": "28 passed: python -m pytest tests/tests_signal.py -q -o addopts=",
  "lint": "ruff check, ruff format --check and git diff --check passed",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "scipy": "1.18.1",
    "pandas": "2.3.3"
  },
  "limitations": "No full package test or total coverage claim"
}
```

</details>

<a id="evidence-neuropsychology-neurokit-1228"></a>

<details>
<summary>neuropsychology/NeuroKit #1228 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/neuropsychology/NeuroKit/pull/1228/files)

```json
{
  "before": "6 regressions fail on dev: KeyError 0 for named single columns, lost column/index labels for mixed frames",
  "after": "17 passed in complete statistics module on each of pandas 2.3.3 and 3.1.0",
  "lint": "ruff check, ruff format --check and git diff --check pass",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pandas": "2.3.3 and 3.1.0",
    "scipy": "1.18.1"
  },
  "limitations": "No full package run or total coverage claim",
  "ci_followup": {
    "pr": "https://github.com/neuropsychology/NeuroKit/pull/1228",
    "parent_commit": "99abde261d7746e8cc904864aa03625c495853ba",
    "cause": "pandas 3 infers text columns as StringDtype; is_string only recognized object, so rolling attempted numeric aggregation on text",
    "before": "3 failed, 7 passed, 7 deselected with explicit object/string regression cases on pandas 3.1.0",
    "after": {
      "pandas 3.1.0": "17 passed in 30.42s",
      "pandas 2.3.3": "17 passed in 24.17s"
    },
    "command": "python -m pytest tests/tests_stats.py -q -o addopts= --tb=short",
    "lint": "ruff 0.17.2 check and format --check on both changed files; git diff --check pass",
    "files": [
      "neurokit2/misc/check_type.py",
      "tests/tests_stats.py"
    ],
    "publication_status": "Published after parent review to the existing PR branch; commit cd066e1c41f3ead81238f68d6eec8d93514c1009",
    "remote_ci": {
      "head": "cd066e1c41f3ead81238f68d6eec8d93514c1009",
      "status": "All Python 3.10-3.14 test jobs, lint/format, package build and documentation build succeeded; deploy and package publication jobs skipped",
      "test_run_url": "https://github.com/neuropsychology/NeuroKit/actions/runs/40119358135"
    }
  }
}
```

</details>

<a id="evidence-nipy-nibabel-1588"></a>

<details>
<summary>nipy/nibabel #1588 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/nipy/nibabel/pull/1588/files)

```json
{
  "before": "4 failed regressions, 21 passed finite-range controls",
  "after": "106 passed across test_scaling.py, test_arraywriters.py and test_volumeutils.py; 68 numeric cast/overflow warnings",
  "lint": "ruff check, ruff format --check and git diff --check passed",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4"
  },
  "limitations": "Full package suite not run"
}
```

</details>

<a id="evidence-jazzband-tablib-710"></a>

<details>
<summary>jazzband/tablib #710 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/jazzband/tablib/pull/710/files)

Regression raises IndexError before fix. Full suite 184 passed after; Ruff and git diff --check pass.

</details>

<a id="evidence-alkaline-ml-pmdarima-625"></a>

<details>
<summary>alkaline-ml/pmdarima #625 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/alkaline-ml/pmdarima/pull/625/files)

```json
{
  "before": "16 failed, 8 passed new numerical cases",
  "after": "52 preprocessing tests passed, 2 existing pandas weekday deprecation warnings",
  "limitations": "Four compiled extensions supplied by installed2.1.1 wheel; source Python modules tested. Full ARIMA suite not run.",
  "flake8": "both changed files passed"
}
```

</details>

<a id="evidence-alkaline-ml-pmdarima-626"></a>

<details>
<summary>alkaline-ml/pmdarima #626 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/alkaline-ml/pmdarima/pull/626/files)

```json
{
  "before": "3 failed, 3 passed",
  "after": "6 metrics tests passed",
  "limitations": "Full ARIMA/model-selection suite not run; installed2.1.1 wheel supplies compiled extensions"
}
```

</details>

<a id="evidence-getsentry-responses-842"></a>

<details>
<summary>getsentry/responses #842 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/getsentry/responses/pull/842/files)

12 regression failures before; 5 controls pass. After: 81 matcher tests and full suite 278 tests pass; 18 existing deprecation warnings. Black, Flake8 and diff checks pass. Same 3 baseline mypy errors reproduced unchanged.

</details>

<a id="evidence-pydicom-pydicom-2409"></a>

<details>
<summary>pydicom/pydicom #2409 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/pydicom/pydicom/pull/2409/files)

```json
{
  "before": "3 new buffered JSON regressions fail with TypeError",
  "after": "640 passed, 5 skipped across test_json, test_dataelem, test_filewriter, test_fileutil; 3 existing validation warnings",
  "lint": "Pinned Ruff0.15.12 check/format and git diff --check pass",
  "typing": "Mypy1.20.2 Python3.12 changed-file check with --follow-imports=silent passes; followed imports report six errors in unchanged pixels/utils.py",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pydicom": "3.1.0.dev0"
  },
  "limitations": "No full package suite, global type pass or documentation build claim"
}
```

</details>

<a id="evidence-neuropsychology-neurokit-1229"></a>

<details>
<summary>neuropsychology/NeuroKit #1229 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/neuropsychology/NeuroKit/pull/1229/files)

```json
{
  "before": "2 regressions fail with incorrect column scaling for ndarray and DataFrame inputs",
  "after": "9 passed in tests/tests_stats.py with -o addopts=",
  "lint": "ruff check, ruff format --check and git diff --check pass",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pandas": "2.3.3"
  },
  "limitations": "No full package suite or total coverage claim"
}
```

</details>

<a id="evidence-pylons-webob-504"></a>

<details>
<summary>Pylons/webob #504 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/Pylons/webob/pull/504/files)

Before: 2 regression failures, 2 passing controls. After: full suite 2395 passed, 3 skipped, 1 xfailed, 14 warnings. Black/diff checks pass.

</details>

<a id="evidence-rlabbe-filterpy-334"></a>

<details>
<summary>rlabbe/filterpy #334 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/rlabbe/filterpy/pull/334/files)

```json
{
  "before": "4 failed, 3 passed",
  "after": "11 passed, 12 deselected in new tests plus existing UKF sigma-point subset",
  "limitations": "Full plotting/filter suite not run; existing SciPy deprecation warnings"
}
```

</details>

<a id="evidence-rlabbe-filterpy-335"></a>

<details>
<summary>rlabbe/filterpy #335 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/rlabbe/filterpy/pull/335/files)

```json
{
  "before": "6 failed, 2 passed",
  "after": "20 passed, 2 existing failures across regression and test_kf.py",
  "baseline_existing": "test_noisy_1d and test_steadystate fail identically on base in mahalanobis float(array)",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "scipy": "1.18.1",
    "pytest": "9.1.1"
  },
  "checks": "flake8 new test and git diff --check pass",
  "limitations": "Full filter/plotting suite not run. Two existing scipy.ndimage deprecation warnings.",
  "encoding": "Remote diff verified after restoring original UTF-8 docstring; only planned RTS changes remain."
}
```

</details>

<a id="evidence-pyserial-pyserial-886"></a>

<details>
<summary>pyserial/pyserial #886 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/pyserial/pyserial/pull/886/files)

Before: 1 regression failure, 5 controls passed. After: 111 passed, 10 skipped; Python 3.12.14/Windows, pytest 9.1.1, pyfakefs 6.2.0. Hardware not tested.

</details>

<a id="evidence-websocket-client-websocket-client-1082"></a>

<details>
<summary>websocket-client/websocket-client #1082 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/websocket-client/websocket-client/pull/1082/files)

Before focused URL suite: 4 new scheme subtest failures plus existing Windows CGI failure, 15 passed and 19 subtests passed. After full suite: 270 passed, 26 skipped, 146 subtests passed, same single CGI failure. Python3.12.14/pytest9.1.1. No internet-enabled tests.

</details>

<a id="evidence-grahamdumpleton-wrapt-363"></a>

<details>
<summary>GrahamDumpleton/wrapt #363 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/GrahamDumpleton/wrapt/pull/363/files)

Before: 3 failed, 2 passed in focused test_formatargspec. After: 1376 passed, 8 skipped, 43 subtests passed in core suite, pure Python only; explicit WRAPT_DISABLE_EXTENSIONS=true same result. Python3.12.14, pytest9.1.1, Black26.10.1 pass. Complete Justfile/C/mypy matrices not run.

</details>

<a id="evidence-pydicom-pydicom-2410"></a>

<details>
<summary>pydicom/pydicom #2410 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/pydicom/pydicom/pull/2410/files)

```json
{
  "before": "2 regression failures: buffer remains at57 instead of original13 after RuntimeError and KeyboardInterrupt",
  "after": "602 passed, 5 skipped across test_fileutil, test_dataelem, test_filewriter; two existing validation warnings",
  "lint": "Pinned Ruff0.15.12 lint/format and git diff --check pass",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pydicom": "3.1.0.dev0"
  },
  "limitations": "No full package or docs build claim"
}
```

</details>

<a id="evidence-imageio-imageio-1250"></a>

<details>
<summary>imageio/imageio #1250 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/imageio/imageio/pull/1250/files)

```json
{
  "before": "2 regression failures, 2 matching-byte-order controls pass",
  "after": "23 passed, 10 skipped: pytest tests/test_pydicom.py -q -m not needs_internet",
  "format": "Black26.10.1 --check, flake8 7.4.1, ruff format --check and git diff --check pass",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pydicom": "3.0.2",
    "imageio": "2.38.1"
  },
  "limitations": "Remote test fixtures excluded; no full package test claim"
}
```

</details>

<a id="evidence-mhe-pynrrd-174"></a>

<details>
<summary>mhe/pynrrd #174 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/mhe/pynrrd/pull/174/files)

```json
{
  "before": "Two truncated trailer cases are incorrectly accepted; two complete-stream controls pass",
  "after": "Full unittest discover nrrd/tests: 161 tests, OK",
  "lint": "flake8 --config=setup.cfg and git diff --check pass",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pynrrd": "1.1.3"
  },
  "warnings": "Existing datetime.utcnow deprecation in unchanged writer.py; already covered by open PR171"
}
```

</details>

<a id="evidence-mhe-pynrrd-175"></a>

<details>
<summary>mhe/pynrrd #175 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/mhe/pynrrd/pull/175/files)

```json
{
  "before": "Four compressed positive-skip subtests error (gzip/bzip2 × byte skip/byteskip); raw and ASCII controls pass",
  "after": "Full unittest discover nrrd/tests: 161 tests, OK",
  "lint": "flake8 --config=setup.cfg and git diff --check pass",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pynrrd": "1.1.3"
  },
  "warnings": "Existing datetime.utcnow writer warning, already addressed by open PR171"
}
```

</details>

<a id="evidence-requests-toolbelt-412"></a>

<details>
<summary>requests/toolbelt #412 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/requests/toolbelt/pull/412/files)

Before focused: 3 failed, 3 passed. After: 6 passed. Nonthreaded suite with 3 narrow existing-deprecation filters: baseline 3 failed,145 passed,5 skipped; fix148 passed,5 skipped. Full threaded suite interrupted/incomplete. Strict warnings fail on baseline Betamax utcnow. Sphinx build succeeds with1 existing-theme deprecation warning. Flake8/diff pass.

</details>

<a id="evidence-c0fec0de-anytree-285"></a>

<details>
<summary>c0fec0de/anytree #285 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/c0fec0de/anytree/pull/285/files)

Before focused:2failed,3passed. After configured full pytest/doctests/cov:236passed,1skipped,98%coverage; Python3.12.14/Windows,pytest9.1.1,PyYAML6.0.3,test2ref1.3.0. Ruff0.17.2 checks/formatpass,Mypy2.4.0 all33filespass,diffpass. Sphinx9.1.1 HTML succeeds29warnings. Initial17missingdiff baseline failures resolved by existingGitdiffPATH.

</details>

<a id="evidence-gorakhargosh-watchdog-1348"></a>

<details>
<summary>gorakhargosh/watchdog #1348 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/gorakhargosh/watchdog/pull/1348/files)

Before:1 failed(None),54passed. After:55queue tests passed; expandedqueue/delayedqueue/observer/events94passed,2unknownflakymarkerwarnings. Python3.12.14/Windows,pytest9.1.1,Ruff0.17.2/Mypy2.4.0 pass. Fullplatformsuite and monkeypatchedqueues notrun.

</details>

<a id="evidence-unit8co-darts-3298"></a>

<details>
<summary>unit8co/darts #3298 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/unit8co/darts/pull/3298/files)

```json
{
  "before": "37 failed, 326 deselected",
  "targeted_after": "48 passed, 315 deselected",
  "module_after": "361 passed, 1 skipped, 1 existing Windows test_from_csv PermissionError",
  "baseline_existing": "test_from_csv same PermissionError on base, 362 deselected",
  "style": "Pinned Ruff0.7.2 from pre-commit config: lint and format checks pass; git diff --check pass",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pandas": "3.0.6"
  },
  "limitations": "Full dev-all/model dependencies were not installed; TimeSeries tests used required lightweight dependencies. NumPy scalar operator dispatch not changed."
}
```

</details>

<a id="evidence-blue-yonder-tsfresh-1138"></a>

<details>
<summary>blue-yonder/tsfresh #1138 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/blue-yonder/tsfresh/pull/1138/files)

```json
{
  "before": "11 failed",
  "after": "96 passed, 3 skipped across regressions and full feature-calculation module with the final range-based fast path",
  "checks": "Black22.12.0 and isort5.12.0 Black profile pass; git diff --check pass",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pandas": "3.0.6",
    "scipy": "1.18.1",
    "numba": "0.68.0"
  },
  "limitations": "Full project suite not run. No performance benchmark or claim. Only 64-bit integer values outside +/-2**52 use exact object arithmetic, at some cost."
}
```

</details>

<a id="evidence-rlabbe-filterpy-336"></a>

<details>
<summary>rlabbe/filterpy #336 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/rlabbe/filterpy/pull/336/files)

```json
{
  "before": "6 regressions fail, plus existing multivariate_gaussian failure",
  "after": "10 passed, 1 existing NumPy2 failure across all stats tests",
  "checks": "flake8 new test and git diff --check pass",
  "limitations": "Full filter suite not run; existing NumPy2 compatibility failure remains."
}
```

</details>

<a id="evidence-rlabbe-filterpy-337"></a>

<details>
<summary>rlabbe/filterpy #337 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/rlabbe/filterpy/pull/337/files)

```json
{
  "before": "3 failed, 3 passed",
  "after": "9 passed, 11 deselected across regression plus existing sequential/batch-filter tests",
  "checks": "flake8 new test and git diff --check pass",
  "limitations": "Full filter/plotting suite not run; existing SciPy warnings."
}
```

</details>

<a id="evidence-rlabbe-filterpy-338"></a>

<details>
<summary>rlabbe/filterpy #338 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/rlabbe/filterpy/pull/338/files)

```json
{
  "before": "4 failed, 2 passed",
  "after": "7 passed, 1 existing failure across regressions and existing IMM module",
  "baseline_existing": "Existing test_imm fails identically on base while constructing simulated trajectory: NumPy2 rejects implicit conversion of 2D array to scalar. Other existing IMM test passes.",
  "checks": "flake8 new test and git diff --check pass",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "scipy": "1.18.1",
    "pytest": "9.1.1"
  },
  "limitations": "Full filter/plotting suite not run; consecutive prediction calls without measurement updates are outside this focused aggregate-prior correction."
}
```

</details>

<a id="evidence-pydata-patsy-277"></a>

<details>
<summary>pydata/patsy #277 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/pydata/patsy/pull/277/files)

```json
{
  "before": "1 failed, 1 passed, 4 deselected: python -m pytest patsy/constraint.py -q -k combine --tb=short; new regression fails TypeError list_iterator is not subscriptable",
  "after": "163 passed in 40.38s: python -m pytest -q --tb=short",
  "lint": "Exact project-pinned Ruff 0.17.1: ruff format --check patsy/constraint.py passed (1 file already formatted); git diff --check passed. No formatting mutation performed.",
  "versions": {
    "python": "3.12.14",
    "patsy_source_version": "1.0.3",
    "numpy": "2.5.4",
    "pandas": "2.3.3",
    "scipy": "1.18.1",
    "pytest": "9.1.1"
  },
  "limitations": "Single Windows/Python dependency environment; no full CI matrix claim"
}
```

</details>

<a id="evidence-alkaline-ml-pmdarima-627"></a>

<details>
<summary>alkaline-ml/pmdarima #627 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/alkaline-ml/pmdarima/pull/627/files)

```json
{
  "versions": {
    "python": "3.12.14",
    "platform": "Windows-11-10.0.26300-SP0",
    "pmdarima": "2.1.1",
    "numpy": "2.5.4",
    "pandas": "3.1.0",
    "scipy": "1.18.1",
    "statsmodels": "0.15.0",
    "sklearn": "1.9.1",
    "pytest": "9.1.1"
  },
  "base_ci_reproduction": "Unmodified base: original pipeline6 fails with read-only error at pipeline.py:478; 1 failed, 66 deselected.",
  "commands": {
    "baseline": "python -m pytest pmdarima/tests/test_pipeline.py -k \"pipeline_predict_inverse_transform and True-True-X0-pipeline6\" -q",
    "new_before": "python -m pytest pmdarima/tests/test_pipeline_readonly.py -q",
    "after": "python -m pytest pmdarima/tests/test_pipeline.py pmdarima/tests/test_pipeline_readonly.py -q",
    "working_directory": "[local path]"
  },
  "new_before": "4 failed",
  "after": "71 passed, 10 pre-existing warnings",
  "style": "flake8 both changed files and git diff --check pass",
  "limitations": "Source Python code tested using compiled 2.1.1 wheel extensions on Windows. Entire project/ARIMA suite and Linux builds not run.",
  "payload": "Both remote blob SHAs match UTF-8/LF local files; complete remote diff contains only one production line plus the new test file."
}
```

</details>

<a id="evidence-bashtage-arch-977"></a>

<details>
<summary>bashtage/arch #977 — validation / validação</summary>

[Implementation and regression tests · Implementação e regressões](https://github.com/bashtage/arch/pull/977/files)

```json
{
  "before": {
    "head": "806d630ed84039354cecec9f6f1470c71e67c0fe",
    "result": "14 tail failures, 8 passing zero/ordinary controls"
  },
  "fresh_base_focused": {
    "base": "2646f9a3da7eb35ec9b940b93fa0274843f7cdb3",
    "result": "22 passed in 6.58s",
    "command": "python -m pytest arch/tests/unitroot/test_normal_tail_pvalues.py -q --color=no"
  },
  "fresh_base_static": "Ruff 0.17.2 lint and format passed for all 3 changed files; git diff --check passed",
  "previous_broad": {
    "head": "806d630ed84039354cecec9f6f1470c71e67c0fe",
    "result": "3679 passed in 140.10s in DynamicOLS/FMOLS/CCR/new-normal-tail module and utility tests; 86 additional existing VarianceRatio cases passed, 406 unrelated cases deselected. The 22 new cases are included in 3679, not counted twice.",
    "repeated_on_new_base": false
  },
  "oracle": "math.erfc(abs(stat)/sqrt(2)), rtol=5e-14, atol=0; actual deterministic data for positive/negative/zero/ordinary VarianceRatio cases",
  "versions": {
    "python": "3.12.14",
    "numpy": "2.5.4",
    "pandas": "3.1.0",
    "scipy": "1.18.1",
    "statsmodels": "0.15.0",
    "pytest": "9.1.1",
    "ruff": "0.17.2"
  },
  "limitations": "Full arch suite, compiled extension builds and multi-version matrix not run. Ignored version metadata only comes from the installed arch 8.0.0 wheel.",
  "evidence": {
    "before": "[local path]",
    "fresh_focused": "[local path]",
    "previous_broad": "[local path]",
    "previous_variance_ratio": "[local path]"
  }
}
```

</details>
