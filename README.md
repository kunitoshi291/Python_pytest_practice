# pytest cache directory

This directory contains data from the pytest's cache plugin,
which provides the `--lf` and `--ff` options, as well as the `cache` fixture.

**Do not** commit this to version control.

See [the docs](https://docs.pytest.org/en/stable/how-to/cache.html) for more information.

### テスト実行

テスト実行するには、pytest コマンドを使う

```
$ pipenv shell
(pipenv) $ pytest test_prime.py
============================================== test session starts ==============================================
事項結果。。。。
=========================================== 1 passed in 0.02 seconds ============================================

```
