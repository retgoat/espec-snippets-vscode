# ESpec Snippets for Visual Studio Code

This extension for Visual Studio Code adds [ESpec](http://rspec.info/) snippets for Elixir.

## Features
- Contain snippets for the most common cases
- Snippets contain ESpec tips
- To be continued...

## Usage

### Base Snippets
| Snippet              | Purpose                                             |
| -------------------- | ----------------------------------------------------|
| `exphmaxby` | expect(Module).to have_max_by(func, value) |
| `expbc` | expect(smth).to be_close_to(expected, delta) |
| `expbt` | expect func |> to(be_true) |
| `letb` | let! :var, do: expr |
| `exphaco` | expect(Module).to have_count(value) |
| `expbfy` | expect func |> to(be_falsy) |
| `expbfunca` | expect func |> to(be_function, aruty) |
| `exphmax` | expect(Module).to have_max(value) |
| `pen` | pending "pending example" |
| `expeq` | expect(smth).to eq(value) |
| `exphacon` | expect Module |> to(have_count value) |
| `subjol` | subject(var) |
| `expn` | expect expression |> to something |
| `xexa` | xexample "skip", do: "skipped" |
| `expend` | expect(smth).to end_with(value) |
| `expbvsn` | expect String |> to(be_valid_string) |
| `expraise` | expect(fn -> Module.func end).to raise_exception(Error, message) |
| `allacc` | allow(Module).to accept(func, fn(args) -> result end) |
| `exphmaxbyn` | expect Module |> to(have_max_by func, value) |
| `expbtpl` | expect smth |> to(be_tuple) |
| `exphcntbyn` | expect Module |> to(have_count_by func, value) |
| `exphavan` | expect Module |> to(have_all fn(x) -> x end) |
| `expbprn` | expect(String).to be_printable |
| `exg` | example_group "description" do … end |
| `expbprnn` | expect String |> to(be_printable) |
| `expbf` | expect func |> to(be_false) |
| `itn` | it do: matcher |
| `expeql` | expect(func).to eql(value) |
| `exphaven` | expect smth |> to(have value) |
| `expbcn` | expect func |> to(be_close_to(expected, delta) |
| `subjn` | subject :var, do: expr |
| `specify` | specify "description", [opts], do: smth |
| `xitb` | xit "description" do … end |
| `exa` | example do: exp |> to matcher |
| `exphat` | expect(Module).to have_at(position, value) |
| `allaccn` | allow Module |> to(accept(func, fn(args) -> result end) |
| `expeqn` | expect func |> to(eq value) |
| `expha` | expect(Module).to have_any(func) |
| `exphmin` | expect(Module).to have_min(value) |
| `expraise` | expect(fn -> Module.func end) |> to(raise_exception Error, message) |
| `exphminn` | expect Module |> to(have_min value) |
| `expeqln` | expect func |> to(eql value) |
| `expbth` | expect func |> to(be_truthy) |
| `foc` | focus "Focused", do: "Focused example" |
| `exphalast` | expect(Module).to have_last(value) |
| `expbits` | expect smth |> to(be_bitstring) |
| `exphal` | expect(Module).to have_length(value) |
| `it` | it "does something" do … end |
| `expbbn` | expect smth |> to(be_binary) |
| `exphan` | expect Module |> to(have_any func) |
| `expbstrus` | expect smth |> to(be_struct, StructExample) |
| `expmatchn` | expect func |> to(match, string) |
| `con` | context "description" do … end |
| `expbe` | expect(smth).to be(operator, value) |
| `expbstru` | expect smth |> to(be_struct) |
| `exphatn` | expect Module |> to(have_at position, value) |
| `exphminbyn` | expect Module |> to(have_min_by func, value) |
| `expbvs` | expect(String).to be_valid_string |
| `xitn` | xit "description" do: "skipped" |
| `expendn` | expect smth |> to(end_with value) |
| `exphave` | expect(Module).to have(value) |
| `expstn` | expect Module |> to(start_with value) |
| `exphminby` | expect(Module).to have_min_by(func, value) |
| `exp` | expect(smth).to something |
| `expchng` | expect func1 |> to(change func2, value) |
| `expbb` | expect(obj).to be_between(expected, delta) |
| `expbbn` | expect func |> to(be_between(expected, delta) |
| `exphst` | expect(Module).to start_with(value) |
| `expmatch` | expect(func).to match(~r/regexp/) |
| `exphsn` | expect Module |> to(have_size value) |
| `exphcntby` | expect(Module).to have_count_by(func, value) |
| `expben` | expect func |> to(be operator, value) |
| `let` | let :var, do: expr |
| `expbatm` | expect smth |> to(be_atom) |
| `expchngft` | expect func1 |> to(change func2, value_from, value_to) |
| `exphalastn` | expect Module |> to(have_last value) |
| `expbfunc` | expect func |> to(be_function) |
| `exphmaxn` | expect Module |> to(have_max value) |
| `exphas` | expect(Module).to have_size(value) |
| `expbli` | expect smth |> to(be_list) |
| `des` | describe "description" do … end |
| `itbl` | it_behaves_like(SharedExample) |
| `tth` | to(${:throw_term} ${2:term})
| `bef` | before do: |
| `incse` | include shared examples |
| `usesp` | use ESpec |
| `consy` | context sync/async |
| `cusmat` | Custom matcher |
| `fnlb` | finally block |
| `fnl` | finally one liner |



## Credits

Many thanks to:
- [ldrner](https://github.com/ldrner) for [RSpec](https://github.com/ldrner/rspec-snippets-vscode/blob/master/LICENSE) snippets and inspiration
- [antonmi](https://github.com/antonmi) for [ESpec](https://github.com/antonmi/espec) library
