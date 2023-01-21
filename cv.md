![avatar](https://i.ibb.co/Fmxfq0W/photo2020.jpg "Иван Коляда")

# Contacts:

- Ivan Koliada
- +375 33 6161903
- [Ivan.Koliada69@gmail.com](mailto:Ivan.Koliada69@gmail.com)

# Objective:

Full stack developer

# Personal qualities / character:

- Hard-working
- Quick training
- Attentive
- Responsible

# Skills:

- Bootstrap 4
- BEM methodology
- Git Intermediate
- HTML Intermediate
- CSS Intermediate
- JS Advanced
- ReactJS Basic
- Redux Basic
- Redux Toolkit Basic
- NodeJS Basic
- NestJS Basic
- REST API Intermediate
- GraphQL Basic
- Websocket Basic
***
# Experience:

WEB-developer udemy course
- JavaScript + React + Redux udemy course
- THE ROLLING SCOPES SCHOOL JAVASCRIPT/FRONT-END 2022Q1
- THE ROLLING SCOPES SCHOOL NodeJS 2022Q4
# Code examples 
```sh
@Get(':id')
@ApiOperation({
  summary: 'Get winner by id',
})

@ApiOkResponse({
  type: [WinnerEntity],
  description: 'OK',
})

@ApiNotFoundResponse({
  schema: { type: 'object' },
  description: 'NOT FOUND',
})

async getWinner(@Param('id', new ParseIntPipe()) id: number) {
  const winner = await this.winnersService.getWinner(id);
  if (winner) return winner;

  throw new HttpException('Winner not found', HttpStatus.NOT_FOUND);
}
```    
# Education:

- End date 2018, Brest State Technical University, Economist, Faculty of Finance and Credit
# Language skills:

- Russian – native
- English - pre-Intermediate